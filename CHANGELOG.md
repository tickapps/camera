# Website changelog

## 2026-10-27 — published via GitHub Pages

- Reorganized the existing English and Chinese iOS photo-report instructions into four numbered steps: open Report, select images, add details, share. Retained the actual limits and platform scope.
- Added only the verified App Store developer display name; did not infer publisher relationships or change structured-data ownership.
- Updated the two changed homepage sitemap dates and the Chinese page's existing `dateModified`.
- Documented the canonical publishing repository, historical ASO draft boundary, missing real report-output asset, and separate store-template correction task.
- Before editing, both homepages matched the 2026-10-27 production readback byte for byte. Pre-change evidence is in the ASO repository under `水印相机/website/live_audit/2026-10-27/`.
- Source commit `9ebb3e0` was pushed to `gh-pages`. Both production homepages and sitemap returned HTTP 200 and matched the source byte for byte on 2026-10-27; the ASO published manifest records the hashes.
- Local validation: both language pages passed `audit_web_discovery.py` with 0 FAIL / 0 WARN / 28 PASS using the current archived response headers and source robots/sitemap; JSON-LD and local links/assets checks passed. This does not establish deployment or indexing.
