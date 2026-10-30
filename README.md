# Lower Stoke Labour — GitHub Pages prototype

A static, responsive prototype based on the approved Lower Stoke design. It does not modify the existing Google Site or lowerstoke.co.uk.

## Before publishing
1. Replace the three grey councillor photo placeholders with genuine photographs.
2. Optionally add a wide genuine Lower Stoke/team image as `assets/hero.jpg`.
3. Review all contact details and links before publication.
4. Replace generic newsletter links in the six Help tiles with exact service/reporting URLs if desired.

## Publish with GitHub Pages
Upload `index.html`, `styles.css` and the `assets` folder to the root of a GitHub repository. In repository Settings → Pages, deploy from the `main` branch/root.

## Photo replacement
For each councillor, replace the `<div class="photo">...</div>` in `index.html` with, for example:

`<img class="photo" src="assets/rupinder.jpg" alt="Cllr Rupinder Singh">`

The CSS already sizes the photo area. Add `object-fit: cover` to `.photo` if using `<img>` elements.
