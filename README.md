# SeongDeok

Personal homepage source for GitHub Pages.

## Deploy

This repository is configured to deploy automatically with GitHub Actions.

1. Push to `main`, `master`, or `work`.
2. In GitHub, go to **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. After the workflow finishes, your site will be available at:
   - `https://<your-github-username>.github.io/<repository-name>/`

For this repository, if owner is `SeongDeok` and repo is `SeongDeok`, the URL will be:

`https://seongdeok.github.io/SeongDeok/`

## Quick verification checklist

After you push, verify in this order:

1. **Actions tab**: `Deploy static site to GitHub Pages` finished with a green check.
2. **Deploy job logs**: `Configure Pages`, `Upload artifact`, and `Deploy to GitHub Pages` all succeeded.
3. **Settings → Pages**: Source is still set to **GitHub Actions**.
4. **Final URL**: Open `https://<your-github-username>.github.io/<repository-name>/` in a browser.
