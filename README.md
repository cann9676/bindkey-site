# BindKey — Site

Marketing site for BindKey, a macOS menu bar app for saving and firing keyboard shortcuts.

Deployed via GitHub Pages at `/bindkey`.

## Structure

```
bindkey-site/
├── index.html       # Main page
├── styles.css       # All styles
├── assets/
│   └── icon.png     # App icon (add this)
└── README.md
```

## Local development

Open `index.html` directly in a browser, or use any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Deployment

This site is deployed as a GitHub Pages **project site**. The final URL is:

```
https://<username>.github.io/bindkey
```

To deploy, push to the `main` branch and enable GitHub Pages in the repository settings (source: `main` branch, root `/`).

## Assets needed

Drop your app icon at `assets/icon.png` (1024×1024 PNG recommended). It's used in the nav, hero section, and download CTA.
