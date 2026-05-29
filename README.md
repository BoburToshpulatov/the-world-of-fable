# Fairy Tale Sequence

This repository contains the production-ready static website for **Fairy Tale Sequence**, a children's iPad fairy-tale sequence game. The landing page presents the app as **The World of Fable**, where children choose a fairy tale, enter story missions, arrange illustrated cards in the correct order, and unlock the next part of the adventure.

The site uses plain HTML, CSS, and a small amount of JavaScript. There is no backend, no build step, and no framework dependency, so it is ready for GitHub Pages.

## File Structure

```text
.
├── index.html
├── privacy.html
├── styles.css
├── script.js
└── assets/
    └── images/
```

## Run Locally

You can open `index.html` directly in a browser.

For local testing with a static server, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Add Images

Place the uploaded island images in:

```text
assets/images/
```

Use these filenames so the website displays them automatically:

```text
assets/images/island-world.png
assets/images/island-forest.png
```

`island-world.png` is used as the main hero visual. `island-forest.png` is used in the feature/gallery areas. If either file is missing, the website shows graceful visual fallbacks so the layout remains polished.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Open the repository settings on GitHub.
3. Go to **Pages**.
4. Set the source to the main branch and the root folder.
5. Save the settings.

GitHub Pages will publish the site from `index.html`.

## App Store Placeholder

The current App Store button points to:

```text
https://apps.apple.com/
```

When the app is published, replace that placeholder URL in `index.html` with the final App Store product link.

## Contact

For questions about the website or app privacy policy, contact:

```text
bobur.vocal@gmail.com
```
