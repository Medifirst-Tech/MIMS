# MIMS
Intelligent  management system for SMEs
# Medifirst CMS
**Clinic Management System**
Version: 1.0 | Status: Phase 1 Complete | Last updated: April 2026

## What This Is
Single-file HTML/CSS/JS clinic management system for Malaysian GP clinics.
Handles: patients, consultation, prescription, billing, inventory, 
documents, lab results, appointments.

## File
- `cms.html` — the entire application (single file, no build step)

## Deploy
1. Download `cms.html`
2. Drag and drop to Netlify
3. Done — live in 30 seconds

## Syncs With
- MIMS (medifirst-mims repo) via BroadcastChannel + localStorage
- Both apps must be hosted on the same Netlify domain

## API Keys Required
- Anthropic API (Claude) — via Netlify proxy at /api/claude
- Set in Netlify environment variables

## Current Build Status
| Module | Status |
|---|---|
| Patient Management | ✅ Complete |
| Prescription + Drug Safety | ✅ Complete |
| Billing + Invoice | ✅ Complete |
| Inventory | ✅ Complete |
| Lab Results | ✅ Complete |
| Documents (8 types) | ✅ Complete |
| Appointments | ✅ Complete |
| Finance Module | 🔄 In Progress |
| Reports | ⬜ Planned |
| Marketing | ⬜ Planned |

## Maintainer
Dr. Rizuan — founder@medifirst.my
