# VectraCode Static Site

This folder is ready to publish as the root of a GitHub Pages repository for
`vectracode.net`.

## Files

- `index.html` - public VectraCode / Control+ landing page.
- `control/privacy/index.html` - public Control+ privacy policy.
- `styles.css` - shared styling.
- `assets/vectracode-brand-mark.png` - cropped VectraCode brand mark.
- `assets/vectracode-logo-source.png` - original VectraCode logo image.
- `assets/control-icon.png` - current Control+ app icon source.
- `CNAME` - GitHub Pages custom domain.
- `.nojekyll` - disables Jekyll processing on GitHub Pages.

## Before Publishing

Replace `LEGAL_PUBLISHER_CONTACT` in `control/privacy/index.html` with the real
legal publisher/contact wording for the first release.

## GitHub Pages Setup

1. Create a public GitHub repository under the `VectraCode` organization.
2. Copy the contents of this folder to the repository root.
3. Push to the `main` branch.
4. Open repository `Settings` > `Pages`.
5. Set `Source` to `Deploy from a branch`.
6. Select branch `main` and folder `/root`.
7. Confirm the custom domain is `vectracode.net`.
8. In Cloudflare DNS, add the records GitHub Pages requests.

After DNS finishes propagating, these URLs should work:

- `https://vectracode.net`
- `https://vectracode.net/control/privacy`
