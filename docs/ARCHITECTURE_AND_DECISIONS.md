# RAFEEQ — ARCHITECTURE PRINCIPLES AND OPEN DECISIONS

## Architecture status
No production architecture is confirmed because the Bolt source has not yet been inspected. Earlier discussions considered Expo/React Native/TypeScript, React Native Web, Node/TypeScript backend, PostgreSQL and SQLite/local files for offline content. These are proposals, not locked decisions. Current explicit tool direction is to import the existing Bolt project into Lovable. Inspect what Bolt actually built before replacing frameworks or backend services.

## Logical domains
- Identity and session management.
- Canonical Quran content and edition metadata.
- Translation/Tafsir library.
- Reciter/riwayah/audio catalogue.
- Tajweed lessons and reviewed learning.
- Prayer configuration/calculation.
- Qibla and device sensors.
- Hadith and dua catalogue.
- User library: bookmarks, progress, downloads and preferences.
- Offline package manager and sync.
- Admin/content management and audit.
- AI explanation gateway with source grounding.

Start as a maintainable modular application. Do not split into microservices without evidence.

## Data principles
- Canonical religious content is versioned and immutable by default.
- User data is private and access-controlled.
- Bookmarks/progress sync safely.
- Offline content carries version/source metadata.
- Audio is stored separately and downloaded on demand.
- Schema changes require migrations, backups and rollback.
- Server validates role and ownership on every privileged operation.

## Security
- Never commit secrets/private data.
- Use provider secret management.
- Enforce admin permissions server-side.
- Least privilege and admin audit logs.
- Protect file uploads/downloads.
- Rate-limit auth/recovery APIs.
- Secure sessions and CSRF protections where applicable.
- Document account export/deletion/retention.
- Do not collect NIN or identity data without a justified lawful requirement.

## Open decisions after source inspection
1. Actual frontend framework and Lovable migration compatibility.
2. Backend/database provider; preserve existing service where possible.
3. Auth provider, roles and account migration.
4. Quran corpus, Mushaf edition/page mapping and licensing.
5. Translation/Tafsir catalog and licenses.
6. Reciter/riwayah catalog and audio rights.
7. Offline storage/sync design.
8. Prayer calculation library/method and user settings.
9. Qibla sensor implementation.
10. Tajweed curriculum and review process.
11. AI explanation scope.
12. Web-first vs native Android packaging.
13. Owner/admin identity and secure access.
14. Hosting, domain, backups and monitoring.

## Decisions recorded
- Preserve Bolt implementation before migration.
- Continue with Lovable is the user's latest explicit direction.
- No final stack replacement approved.
- No production payment/monetization feature confirmed.
- No public admin access or exposed owner credentials.
- Accuracy and offline reliability outrank feature count.