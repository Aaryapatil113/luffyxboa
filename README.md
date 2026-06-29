# LuffyxBoa 💛

A little website made with love — mini games and memories.

## Project structure

```
luffyxboa/
├── index.html          ← home page
├── css/
│   └── style.css       ← shared styles
├── games/
│   ├── bubbles.html    ← pop the bubbles
│   ├── hearts.html     ← catch the hearts
│   └── memory.html     ← memory match
└── photos/             ← drop your photos here
```

## Adding photos

1. Drop your image files into the `photos/` folder (jpg, png, webp all work)
2. Open `index.html` and find the `photos-grid` section
3. Replace the placeholder `<div class="photo-slot">` blocks with:

```html
<div class="photo-slot">
  <img src="photos/your-photo-name.jpg" alt="us" />
</div>
```

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `luffyxboa`)
2. Clone it locally and drop all these files in
3. Push to `main`
4. Go to repo Settings → Pages → Source: `main` branch → Save
5. Your site will be live at `https://yourusername.github.io/luffyxboa/`
