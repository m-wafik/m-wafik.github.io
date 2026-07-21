# Personal website — deployment steps

This folder is a complete static site: `index.html`, `research.html`, `teaching.html`,
`cv.html`, `style.css`, and `Mohamed_Wafik_ElSheikh_CV.pdf`. No build step needed.

## Publish it with GitHub Pages (free)

1. Go to github.com and create a new **public** repository.
   - If you want the site at `https://<your-username>.github.io/`, name the repo exactly
     `<your-username>.github.io`.
   - Any other name works too — the site will just live at
     `https://<your-username>.github.io/<repo-name>/` instead.
2. Upload all the files in this folder to the root of that repository (drag-and-drop works
   on github.com, or `git add . && git commit -m "site" && git push` if you're using the
   command line).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", pick the
   **main** branch and the **/ (root)** folder, then save.
5. GitHub will give you the live URL in that same settings page within a minute or two.

## Updating later

Just edit the `.html` files directly (they're plain text) and push the changes — no
rebuild step. If you replace the CV PDF, keep the filename
`Mohamed_Wafik_ElSheikh_CV.pdf` or update the link in `cv.html` to match.
