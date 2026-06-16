# DepthScope Support Page

This folder is a standalone GitHub Pages handoff for the App Store `Support URL` field.

## Recommended publish target

Use the existing public repository:

`miyachin-paperdriver/public-pages`

Recommended path inside that repository:

`depthscope-support/`

Expected published URL:

`https://miyachin-paperdriver.github.io/public-pages/depthscope-support/`

## Files

- `index.html`: the support page
- `.nojekyll`: optional Pages helper file

## Publish steps

1. Open the `miyachin-paperdriver/public-pages` repository.
2. Create a folder named `depthscope-support`.
3. Copy the contents of this folder into `public-pages/depthscope-support/`.
4. Push the repository to GitHub.
5. Ensure GitHub Pages is enabled for `main` and `/ (root)`.
6. Confirm that `https://miyachin-paperdriver.github.io/public-pages/depthscope-support/` loads without login.
7. Paste that URL into App Store Connect as the `Support URL`.

## Notes

- The current support route uses the public repository issues page and the public GitHub profile.
- If you later prepare a dedicated support email address or external support form, update the links in `index.html`.
- The privacy policy page is expected to live at `../depthscope-privacy-policy/` on the same Pages site.