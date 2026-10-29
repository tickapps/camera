# Website changelog

## 2026-10-29 — iOS 1.7.0 template naming

- Listed the six confirmed iOS 1.7.0 template names in English and Simplified Chinese, with a dated awaiting-review notice and the current 1.6.3 release state. Kept Android names unchanged.
- Added the upcoming two-column list with high-resolution scene previews, five-language naming, and landscape video watermark spacing/positioning fix.
- Replaced stale iOS template-name references in feature explanations, examples, captions and English FAQ with version-neutral feature wording; retained confirmed template-specific field boundaries without inferring every old/new field mapping.
- Removed the `2.jpg` figure, which was incorrectly labelled as the template-selection interface, from both homepages. Retained its source asset. User-supplied English and Chinese iOS 1.7.0 test-build screenshots replace it on the respective pages, using locale-specific assets paths, original dimensions and full-size links; captions identify the pending app release.
- Updated homepage sitemap dates and the Chinese WebPage dateModified. Kept locale routing, store links, privacy and terms unchanged.
- Pre-change production HTML, headers and hashes are archived in ASO under `水印相机/website/live_audit/2026-10-29-template-names/`.

## 2026-10-27 — published via GitHub Pages

- Reorganized the existing English and Chinese iOS photo-report instructions into four numbered steps: open Report, select images, add details, share. Retained the actual limits and platform scope.
- Added only the verified App Store developer display name; did not infer publisher relationships or change structured-data ownership.
- Updated the two changed homepage sitemap dates and the Chinese page's existing `dateModified`.
- Documented the canonical publishing repository, historical ASO draft boundary, missing real report-output asset, and separate store-template correction task.
- Before editing, both homepages matched the 2026-10-27 production readback byte for byte. Pre-change evidence is in the ASO repository under `水印相机/website/live_audit/2026-10-27/`.
- Source commit `9ebb3e0` was pushed to `gh-pages`. Both production homepages and sitemap returned HTTP 200 and matched the source byte for byte on 2026-10-27; the ASO published manifest records the hashes.
- Local validation: both language pages passed `audit_web_discovery.py` with 0 FAIL / 0 WARN / 28 PASS using the current archived response headers and source robots/sitemap; JSON-LD and local links/assets checks passed. This does not establish deployment or indexing.
