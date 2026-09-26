# Rohit Duvvuru — Robotics Portfolio Website

This folder is deployment-ready and has no build dependencies.

## Preview locally

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new GitHub repository (for example `robotics-portfolio`).
2. Copy the contents of this folder into the repository root.
3. Commit and push.
4. In GitHub: **Settings → Pages → Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.

## Deploy to Vercel

1. Push this folder to GitHub.
2. Import the repository into Vercel.
3. Framework preset: **Other**.
4. No build command is required.
5. Output directory: `.`

## Edit content

- Main page: `index.html`
- Styling: `styles.css`
- Images: `assets/images/`
- Videos: `assets/videos/`
- Resume: `assets/docs/Rohit_Duvvuru_Resume.pdf`
