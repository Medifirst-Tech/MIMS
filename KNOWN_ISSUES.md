# Known Issues — Medifirst MIMS

## Open Issues
*No open issues currently*

---
## Closed Issues

### [MIMS-001] API key exposed in public repo — RESOLVED v1.1.0
- **Status:** ✅ Resolved in v1.1.0
- **What happened:** ANTHROPIC_API_KEY was hardcoded in index.html — exposed when repo went public
- **Fix:** All 14 AI calls routed through /api/claude Netlify proxy. Key moved to Netlify env vars only
- **Action taken:** Old key revoked, new key issued
