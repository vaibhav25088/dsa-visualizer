# DSA Algorithm Visualizer & Problem Solver (Web)

A single-page website to learn sorting, searching, stack and queue step by step.
Pure HTML, CSS and JavaScript. No build step, no dependencies, works offline.

## Features
- Sorting: Bubble (early exit), Selection, Insertion with Step / Run all / Finish / Reset
- Searching: Linear and Binary (binary searches a sorted copy)
- Stack (LIFO) and Queue (FIFO, circular array) with overflow and underflow handling
- Step log, live counters, complexity explanation, DSA concepts tab
- Input validation (max 100 integers)

## Run locally
Double-click `index.html`, or from this folder run `python -m http.server 8000` and open http://localhost:8000

## Deploy on GitHub Pages
1. Create a new repository on github.com (e.g. `dsa-visualizer`).
2. Upload these files (`index.html`, `README.md`, `.nojekyll`) or push with git:
   ```
   git init
   git add .
   git commit -m "DSA visualizer website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/dsa-visualizer.git
   git push -u origin main
   ```
3. On GitHub: Settings > Pages > Source: "Deploy from a branch" > Branch: `main` / `(root)` > Save.
4. After 1-2 minutes the site is live at `https://<your-username>.github.io/dsa-visualizer/`.

## Author
[Your name]
