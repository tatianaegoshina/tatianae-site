# Tatiana Egoshina

A one-page portfolio holding site, independent of Framer. Plain HTML and CSS; no installation or build step.

## Preview

Run `python3 -m http.server 8080` in this folder, then open http://localhost:8080.

## Hosting

Publish with GitHub Pages: **Settings → Pages → Deploy from a branch → main → / (root)**. The same files also work on any static hosting service.

Connect `tatianae.com` only when ready to replace the current Framer site. Add the custom domain in GitHub Pages, then apply the DNS records GitHub displays. Keep existing email MX/TXT records. This repository deliberately has no CNAME file until the domain is connected.

## Editing

- `index.html`: name, biography, Instagram, email and Vimeo embed URL.
- `styles.*.css`: layout, type sizes and responsive styles.
- `inter-latin-regular.woff2`: locally hosted Inter Regular, with its license in `OFL.txt`.

The desktop layout follows the original site's 20px outer padding, 22px type, two columns, 20px column gap and 40px space before the biography. The typeface is Inter as requested.

The Vimeo background uses `background=1`, autoplay, loop, muted playback, no controls, no keyboard focus and no pointer interaction. It covers the viewport using the verified 1526 × 1010 video ratio, cropping edges as needed, with the focal point at 25% of the width to retain the person and crop more of the bicycle on narrow screens. Mobile uses a single column. Vimeo must continue allowing this video to be embedded on the published domain. Browser or device autoplay restrictions can still prevent playback in low power or restrictive data modes; the page remains readable over its dark fallback background.
