# DepthScope Privacy Policy Page

This folder is a standalone GitHub Pages handoff for the App Store `Privacy Policy URL` field.

## Why this is outside the app repo

The current app source repository is private. For App Store review, the privacy policy URL should be publicly reachable without authentication. The simplest setup is a separate **public** repository under `miyachin-paperdriver`.

## Recommended publish target

Use the public repository you created: `miyachin-paperdriver/public-pages`.

Because that repository may host multiple pages, keep this privacy policy in its own subfolder.

Recommended path inside `public-pages`:

`depthscope-privacy-policy/`

If GitHub Pages is enabled for the `public-pages` repository, the expected URL for this page will be:

`https://miyachin-paperdriver.github.io/public-pages/depthscope-privacy-policy/`

## Files

- `index.html`: the privacy policy page
- `.nojekyll`: optional Pages helper file

## Publish steps

1. Open the `miyachin-paperdriver/public-pages` repository.
2. Create a folder named `depthscope-privacy-policy` in that repository.
3. Copy the contents of this folder into `public-pages/depthscope-privacy-policy/`.
4. Push the repository to GitHub.
5. Open the repository settings on GitHub.
6. Go to `Pages`.
7. Set `Source` to `Deploy from a branch`.
8. Select branch `main` and folder `/ (root)`.
9. Save and wait for GitHub Pages to publish.
10. Open `https://miyachin-paperdriver.github.io/public-pages/depthscope-privacy-policy/` and confirm it loads without login.
11. Paste that URL into App Store Connect as the `Privacy Policy URL`.

## Optional cleanup before publish

- If you want a dedicated contact route, replace the GitHub profile link in `index.html` with a public support email or support page.
- If you later need a separate App Store `Support URL`, add a sibling page such as `support/index.html` or `depthscope-support/index.html` in the same `public-pages` repository.

## Alternative: account site

If you prefer an account-wide Pages repository such as `miyachin-paperdriver.github.io`, you can place this page in a subfolder like `depthscope-privacy-policy/` and use the resulting path URL instead.