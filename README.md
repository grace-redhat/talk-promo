# AI Infra Summit Flyer

A single-page flyer for "Securing AI Agents at Runtime" (AI Infra Summit, Sep 16, 11:00 AM — Data & Models Track).

## Files

- `index.html` — the flyer page
- `grace-cutout.png` — cutout photo used in the photo slot
- `.nojekyll` — tells GitHub Pages to serve the files as-is (no Jekyll processing)

## Publish to GitHub Pages

1. Create a new GitHub repository (public, or private on a plan that supports Pages).
2. Push this folder's contents to it:

   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git branch -M main
   git push -u origin main
   ```

3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to "Deploy from a branch," pick the `main` branch and `/ (root)` folder, then save.
5. GitHub will publish the site at `https://<your-username>.github.io/<your-repo>/` within a minute or two.

This folder is already a git repository with an initial commit, so step 2 is all that's needed to get it onto GitHub.
