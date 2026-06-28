# Muhammad Usman Ashraf Personal Website

Static personal website for GitHub Pages.

## Files

- `index.html`: website content
- `styles.css`: design and layout
- `script.js`: footer year script
- `assets/Muhammad_Usman_Ashraf_CV.pdf`: downloadable CV
- `.nojekyll`: serves files directly on GitHub Pages

## Publish

1. Create a public GitHub repository named `Mughal789.github.io`.
2. Upload all files from this folder into the repository root.
3. Go to Settings, then Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Select `main` and `/root`.
6. Save and wait for the website to publish.

## Upload or replace CV

1. Open the repository on GitHub.
2. Open the `assets` folder.
3. Click Add file, then Upload files.
4. Upload your CV PDF.
5. Use this exact filename if you want the Download CV button to work without editing code:

`Muhammad_Usman_Ashraf_CV.pdf`

6. Commit the change.

If you use a different filename, update this line in `index.html`:

`href="assets/Muhammad_Usman_Ashraf_CV.pdf"`
