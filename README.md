# Cozy Stitches - Static Site

This is a simple static website to showcase handmade items (scarves, socks, etc.). It includes:

- Welcome page: `index.html`
- Shop page: `shop.html`
- Who am I page: `about.html`

## How to open

No build is required. Double-click any of the HTML files, or open with a local server:

```bash
# Using PowerShell
pwsh -NoProfile -Command "Start-Process http://localhost:5500; cd $PWD; npx --yes live-server --port=5500 --no-css-inject"
```

If you prefer without a server, open `index.html` in your browser.

## Customize

- Replace placeholder blocks (purple stripes) with images in `img/` and update `<img>` tags as needed. Current templates use `.placeholder-img` blocks for convenience.
- Update contact details in `about.html` (email, Instagram).
- Add or edit products in `shop.html` by duplicating a `.product-card`.
- Adjust colors and spacing in `css/styles.css`.

## File structure

```
/ (project root)
├─ index.html
├─ shop.html
├─ about.html
├─ css/
│  └─ styles.css
└─ README.md
``` 