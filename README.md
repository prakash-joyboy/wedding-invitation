# Prakash & Geetha — Wedding Invitation

Static wedding invitation site (HTML/CSS/JS). No build step required.

## Local preview

```bash
cd wedding-invite
python3 -m http.server 8080
```

Open http://localhost:8080

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages → Source**: Deploy from branch `main` / folder `/ (root)`.
3. Site URL will be `https://<user>.github.io/<repo>/`.

Or enable the included GitHub Actions workflow for Pages.

## Customize

Edit the `INVITE` object near the bottom of `index.html` (names, date, venue, maps query).
