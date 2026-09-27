# Yuvraj RO Sales Service Center: Design Preview

An independent, responsive website proposal for the Panki, Kanpur business.
This is not the business's official website. The visual layout is adapted from
the existing RO design demo; the business content and photographs are Yuvraj's.

## Preview and Hosting

- GitHub Pages preview: https://gopalshuklacanva.github.io/yuvraj-ro-sales-demo/
- Serve the repository root; entry point is `index.html`.
- No build, packages, database, credentials or environment variables are needed.
- GitHub Pages publishes the `main` branch root. Keep `.nojekyll`.
- Keep the independent-preview footer, `noindex, nofollow` and `robots.txt`
  until an official launch is approved. These are not access controls:
  the demo and repository are public.
- This deployment is a design proposal for review. For an official commercial
  launch, confirm the host's current terms and obtain business-owner approval.

## Content

Name, address, phone, hours, 5.0 rating and 359 reviews were checked directly
on Google Maps on 27 September 2026. They are a dated snapshot, not a live feed.
See `SOURCES.md` for provenance. Confirm current services and model availability
with the business before treating this as an official site.

The gallery contains six unchanged files from the owner-posted Maps collection.
The hero is an AI-edited transparent cutout based on its Aqua Natural product
image; the original is also in the gallery. It is not a new customer installation
or a photo of a different business. Fine printed product details in the hero
may differ from the source because of the AI edit.

Photos, product trademarks and review excerpts retain their original ownership.
Obtain the relevant permission for continuing official use. No blanket license
for the business's media is granted by this repository. Manrope's license is
included in `assets/manrope-license.txt`.

## Checks

Open `index.html` in a browser. The mobile menu, gallery filters and photo viewer
work without a backend. All call links use `tel:+917905467387`; map links go to
the verified Yuvraj listing. No form collects visitor data or takes payments.

Run `node --check site.js` to check JavaScript syntax.
