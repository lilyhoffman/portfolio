# Portfolio

A responsive, buildless, three-page portfolio for GitHub Pages. No dependencies, accounts, or API keys are needed to run it.

## Preview
Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages
1. Sign in to GitHub as `lilyhoffman` and create a public repository named `lilyhoffman.github.io`. If it already exists, review its contents before replacing anything.
2. Upload the CONTENTS of this folder to the repository root. Keep the `assets` folder intact. `index.html` must be at the root, not inside a second `lily-portfolio` folder.
3. Commit the files to `main`.
4. Open Settings → Pages. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, and Save.
5. Wait for GitHub's deployment to finish, then visit https://lilyhoffman.github.io/.

For a differently named repository, the same relative paths work at https://lilyhoffman.github.io/REPOSITORY-NAME/.

## Update
- `index.html`: introduction and project previews.
- `projects.html`: project explanations and architecture flows.
- `experience.html`: professional experience and education.
- `styles.css`: shared colors, layout, typography, and mobile styles.
- `assets/lily-hoffman-resume.pdf`: replace this file when your résumé changes, retaining the filename.

Contact links appear in the footer on all three pages. Project links point to the project folders in the data-engineering-portfolio repository. The cloud project's Terraform description follows its README: definitions were validated, while live resources were created manually.

The public PDF includes contact information from the supplied résumé. Review all content before sharing the deployed URL. This package has not been published to GitHub.
