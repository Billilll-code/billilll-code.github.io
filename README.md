# Portfolio site

Static site, no build step — just HTML/CSS. Ready to push straight to `yourusername.github.io`.

## Before you go live, replace these placeholders

**In `index.html`:**
- `https://github.com/yourusername` — your real GitHub profile (appears 3 times)
- `https://github.com/yourusername/your-repo` — link each project to its actual repo (2 places)
- `your.email@example.com` — your real email
- `https://linkedin.com/in/yourprofile` — your real LinkedIn, or delete that line if you'd rather not include it

**In `assets/`:**
- Add your CV as `assets/Julian_CV.pdf` (exact filename), then delete `PUT_CV_HERE.txt`

## Running it locally before you push

Just open `index.html` in a browser — no server needed. Or, for a closer-to-production preview, run a tiny local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — page structure and content
- `style.css` — all styling
- `assets/` — CV and any images you add later