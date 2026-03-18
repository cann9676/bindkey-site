# BindKey — Site

Marketing site for BindKey, a macOS menu bar app for saving and firing keyboard shortcuts.

## File structure

```
bindkey-site/
├── index.html       # Main page
├── styles.css       # All styles
├── assets/
│   └── icon.png     # App icon
└── README.md
```

## Local development

Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
# or
python3 -m http.server
```

## Deploying to GitHub Pages

This site is designed to be deployed as a GitHub Pages **project site** with no build step.

**First-time setup:**

1. Push this repository to GitHub (repo name: `bindkey`)
2. Go to **Settings → Pages** in the repository
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main`, folder to `/ (root)`
5. Click **Save**

GitHub will publish the site at:

```
https://<your-username>.github.io/bindkey
```

**Subsequent deploys:**

Push to `main`. GitHub Pages rebuilds automatically within ~60 seconds.

## Before going live

- Replace `PURCHASE_LINK_HERE` in `index.html` with your Lemon Squeezy checkout URL
- Add the real app icon at `assets/icon.png` if not already present
