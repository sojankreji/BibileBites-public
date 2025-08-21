Landing page for Bible Bites

Files:
- index.html — main landing page (uses `../assets/logoFull.jpg` for the logo)
- styles.css — styles and color tokens matched to the app

How to preview locally

Using Python 3 (quick):

```bash
# from the project root
cd landingpage
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Or use the VS Code Live Server extension and open `landingpage/index.html`.

Notes
- The Play Store link points to `com.aeskae.bible_bites`. If your package id differs, update the links in `index.html`.
- The page references the app logo at `../assets/logoFull.jpg`. If you want a web-optimized logo, place a copy in `landingpage/assets/` and update the paths.
