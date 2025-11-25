# Armando Tile & Stone

Static marketing site for a tile installation company. No build step required—just host the HTML/CSS.

## Local preview

```bash
open index.html # or double-click in your file explorer
```

## Deploy to GitHub Pages

1. Commit these files to your GitHub repository (e.g., `main` branch).
2. In GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**. Select your branch (e.g., `main`) and folder `/**root**` (not `/docs`), then save.
4. GitHub will publish to `https://<your-username>.github.io/<repo-name>/` within a minute.

## Customize

- Update contact info in `index.html` under the **Contact** section and hero panel CTA links.
- Replace color variables and typography in `styles.css` to match your brand.
- Swap gallery tiles with real project photos by setting `background-image` on `.gallery__item` classes.
