# Prakash & Geetha — Wedding Invitation

Static wedding invitation site (HTML/CSS/JS). No build step required.

## Local preview

```bash
cd wedding-invite
python3 -m http.server 8080
```

Open http://localhost:8080

## Deploy to GitHub Pages

From this folder:

```bash
# 1) Sign in (one time)
gh auth login -h github.com -p https -w

# 2) Create the repo and push
gh repo create wedding-invite --public --source=. --remote=origin --push

# 3) Turn on Pages: repo Settings → Pages → Source = GitHub Actions
#    (workflow already in .github/workflows/pages.yml)
```

Live URL will be: `https://<your-username>.github.io/wedding-invite/`

## Customize

Edit the `INVITE` object near the bottom of `index.html` (names, date, venue, maps query).
