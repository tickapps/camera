# Timestamp Camera website

Production website: https://camera.appro7.com/ (English), https://camera.appro7.com/zh-cn/ (简体中文).

This repository is the GitHub Pages publishing source: `tickapps/camera`, branch `gh-pages`. The English page is `index.html`; the Chinese page is `zh-cn/index.html`; `en/index.html` redirects to the English root. Ordinary pushes to the publishing branch must be followed by a Pages build/deployment check and a readback from the production domain.

ASO's `水印相机/website/index_v2.html` and `index_v3.html` are historical archives/drafts, not the publishing source. Do not copy them over this repository. The ASO project maintains product facts and dated production evidence separately.

## Content boundaries

- Preserve the six current templates and platform-specific feature limitations. The iOS report instructions describe real supported behavior; imported images are not watermarked, reports start fresh and are not saved inside the app, and dragging/cropping are unsupported.
- No verified report-output image was supplied for the 2026-10-27 update. Keep the text workflow; add a real, privacy-reviewed app-generated example when available. Do not fabricate a report screenshot.
- The App Store developer display name was verified as `泽沛 许` on 2026-10-27. This does not establish a legal relationship with the site's existing `Xiaomei Photo Studio` branding. Google Play's current publisher display was not freshly retrievable in this check; do not infer or publish a relationship.
- The live English App Store description still used older template names in the 2026-10-27 check. Correcting that listing is a separate authorized store task; do not revert accurate website content to match the stale listing.

Changes and release status: [CHANGELOG.md](CHANGELOG.md).

2026-10-27 release verified: content commit `9ebb3e0` is live; English/Chinese homepages and sitemap match production byte for byte.

## 2026-10-29 template-name update

The homepage now distinguishes the submitted iOS 1.7.0 names from unchanged Android names. The iOS section is explicitly dated and labelled awaiting review; current public iOS release remains 1.6.3 at the check. This is a live website describing an upcoming app update, not a claim that iOS 1.7.0 has launched.

The misleading `2.jpg` figure has been removed from both pages; the source asset remains. It is promotional timestamp artwork, not the template-selection UI. The user subsequently supplied real English and Simplified Chinese iOS 1.7.0 test-build screenshots. They now appear in the respective homepages from locale-specific assets paths, unchanged at 1179×2556 and with full-size links; captions retain the awaiting-review status. Other page routing, store URLs and privacy documents remain unchanged.
