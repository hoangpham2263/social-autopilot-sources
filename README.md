# social-autopilot-sources

Public image host for social-autopilot. Only images of posts that a person has already approved are pushed here, so Metricool can fetch them by URL.

Layout: `<brand>/<yyyy>/<mm>/<post-id>.<ext>`

Link format: `https://raw.githubusercontent.com/hoangpham2263/social-autopilot-sources/main/<brand>/<yyyy>/<mm>/<post-id>.jpg`

Rules:
- Approved post images only. No drafts, no competitor reference photos, no source/raw files.
- Images have metadata stripped before upload.
- Files can be removed once Metricool has saved its own copy.
