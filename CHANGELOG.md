# Changelog — Medifirst MIMS

## [v1.1.0] — 2026-04-14
### Security
- Removed hardcoded ANTHROPIC_API_KEY from HTML source
- All 14 AI calls now route through /api/claude Netlify proxy
- API key secured in Netlify environment variables only

---
## [v1.0.0] — 2026-04-01
- Initial MIMS release

---
## [v1.2.0] — 2026-04-14
### Changed
- Role-based nav: CEO Dashboard restricted to CEO only
- Staff Management restricted to CEO + Manager
- All other pages open to staff for testing phase
- navTo() page guard prevents direct URL bypass
