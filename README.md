# Minimal personal site (GitHub Pages ready)

A dependency-free static website inspired by the *structure* of nfwolf.com: a compact personal home page with an avatar, social links, and a dedicated about page.

## Customize

Search these files for the placeholder values and replace them:

- `Your Name`
- `yourhandle`
- `hello@example.com`
- `Your city, country`
- social URLs in `index.html` and `about.html`
- `assets/avatar.svg` (replace it with your own image if you want; then update the `src` paths)

Colors and spacing live at the top of `styles.css` under `:root`.

## Preview locally

From this directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload everything in this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your default branch (usually `main`) and the `/ (root)` folder.
6. Save. GitHub will publish the site at your Pages URL.

No build step, package manager, or framework is required.
