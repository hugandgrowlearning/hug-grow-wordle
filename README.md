# Hug & Grow Wordle

A no-server seasonal Wordle-style activity for GitHub Pages.

## Publish on GitHub Pages
1. Create a new GitHub repository (for example `hug-grow-wordle`).
2. Upload `index.html`, `style.css`, and `script.js` to the repository root.
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. GitHub will show the public Pages address after deployment.

## Edit words
Open `script.js`. The `THEMES` object at the top contains the 30 answers for each seasonal theme. Keep exactly 30 if you want the interface to continue saying “Game X of 30.”

Answers can have different lengths. Spaces/punctuation are automatically removed for gameplay.

## Customize mode
A teacher can type an answer locally and hand the device to the student. The answer is removed from the visible setup screen, but this is a front-end activity, not secure secret storage.
