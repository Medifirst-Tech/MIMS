# Changelog — Medifirst MIMS

## [v1.2.2] — 2026-04-14
### Fixed
- Correct Claude model name: claude-sonnet-4-5 (no date suffix)
- _claudeFetch now throws descriptive errors instead of silent failures
- My Coach AI fully operational

---
## [v1.2.1] — 2026-04-14
### Fixed
- Wrong Claude model name causing all AI features to fail
- Updated 13 calls from claude-sonnet-4-20250514 → claude-sonnet-4-5-20251001

---
## [v1.2.0] — 2026-04-14
### Changed
- Role-based nav: CEO Dashboard restricted to CEO only
- Staff Management restricted to CEO + Manager
- All other pages open to staff for testing phase
- navTo() page guard prevents direct URL bypass

---
## [v1.1.0] — 2026-04-14
### Security
- Removed hardcoded ANTHROPIC_API_KEY from HTML source
- All 14 AI calls now route through /api/claude Netlify proxy
- API key secured in Netlify environment variables only

---
## [v1.0.0] — 2026-04-01
- Initial MIMS release
