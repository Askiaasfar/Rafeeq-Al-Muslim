# RAFEEQ — CURRENT STATE AND EVIDENCE

**Inspected:** 2026-11-24  
**Repository:** Askiaasfar/Rafeeq-Al-Muslim  
**Branch:** main  
**Visibility:** Public  
**Bolt project supplied by owner:** https://bolt.new/p/72810655

## Verified observations
- GitHub repository exists.
- Initial root contained only README.md with text “# Rafeeq-Al-Muslim / The quran”.
- Owner supplied the Bolt project link.
- Available web/GitHub access could not inspect Bolt project contents.
- This repository is being populated with project documentation first.

## Evidence table
| Area | Status | Evidence |
|---|---|---|
| Product vision | RECOVERED | Prior conversation context |
| Bolt source in GitHub | NOT VERIFIED | Root initially had README only |
| Lovable migration | PLANNED | User's latest direction |
| Database/user migration | UNKNOWN | No export inspected |
| Quran corpus/provenance | UNKNOWN | No content files inspected |
| Audio/riwayah | UNKNOWN | No implementation inspected |
| Tajweed engine | UNKNOWN | No implementation inspected |
| Prayer/Qibla | UNKNOWN | No implementation inspected |
| Offline capability | UNKNOWN | No offline test |
| Admin/auth | UNKNOWN | No source/permission audit |
| Android APK | UNKNOWN | No build inspected |
| Production deployment | UNKNOWN | No deployment inspected |

## Next evidence to collect
1. Export the Bolt project as a ZIP and preserve an untouched backup.
2. Inspect file list and source before import.
3. Exclude secrets, .env values, node_modules, caches and build output.
4. Identify framework, backend, database, auth, storage, API routes, integrations and deployment.
5. Inventory routes, screens, workflows, current errors and tests.
6. Export database schema/data and user records separately through secure supported methods.
7. Import code into Lovable and compare behavior with Bolt.
8. Test critical flows before any production switch.

Never assume the Bolt URL can be imported directly. Never replace the original Bolt project. Do not upload secrets, private identity data or raw production records to this public repository.