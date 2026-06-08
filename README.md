# Dhe Yeong Tchalla — GitHub Pages Website

This is a clean academic research portfolio website for GitHub Pages.

## How to publish

1. Create a GitHub repository named: `dheyeongtchalla.github.io`
2. Upload all files from this folder to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save. Your website should appear at:

`https://dheyeongtchalla.github.io`

## Update profile photo

Replace the initials avatar in `index.html` with your real photo by adding your image to:

`assets/img/profile.jpg`

Then replace:

```html
<div class="avatar">DY</div>
```

with:

```html
<img class="avatar-img" src="assets/img/profile.jpg" alt="Dhe Yeong Tchalla">
```

Then add this CSS to `assets/css/style.css`:

```css
.avatar-img {
  width: 132px;
  height: 132px;
  border-radius: 50%;
  object-fit: cover;
  margin: 0 auto 18px;
  display: block;
  border: 6px solid #eef4ff;
}
```
