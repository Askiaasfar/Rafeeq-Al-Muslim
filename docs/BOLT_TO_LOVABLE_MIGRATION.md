# SAFE MIGRATION: BOLT.NEW TO LOVABLE

## Direction
The owner supplied https://bolt.new/p/72810655 and wants to continue Rafeeq in Lovable because waiting for Bolt credits interrupts progress.

Lovable announced a project-import workflow on 2026-10-29. Its official import page describes importing Bolt projects via ZIP export: https://lovable.dev/free-import. This is a migration/rebuild process, not a direct live link between the Bolt workspace and Lovable.

## Phase A — preserve Bolt
1. Open the existing Bolt project and confirm it is Rafeeq.
2. Export/download the complete code as ZIP.
3. Keep an untouched dated backup.
4. If Bolt GitHub sync is used, connect it only to a separate code repository after confirming its destination; do not overwrite this documentation repository.
5. Record export date, branch/commit if available and project version.
6. Do not delete, disconnect or overwrite Bolt.

## Phase B — inspect the export
1. Inspect ZIP contents before upload.
2. Exclude .env files, API keys, private certificates, node_modules, caches, build output and production data.
3. Include safe source, package manifests, lockfile, public assets, migration files, config templates and tests.
4. Use an .env.example with variable names and placeholders only.
5. Identify backend/data dependencies and provider-specific services.
6. Export database schema/data and user records separately through secure provider-supported methods. Never commit raw production data to this public repository.
7. Identify auth provider, password/session portability and uploaded file storage.

## Phase C — import
1. Open Lovable dashboard.
2. Choose + then Import project to Lovable.
3. Select Bolt and follow its guided export/upload steps.
4. Upload the clean ZIP.
5. Review the generated conversion and preview.
6. Enter required service keys only through Lovable's secure secrets interface, never in chat or committed files.
7. Review data mappings before importing any database or user records.
8. Keep Bolt intact and available until Lovable passes acceptance tests.

## Phase D — parity tests
Compare all routes, pages and workflows:
- Quran Arabic, RTL, diacritics, Surah/ayah/page/Juz navigation.
- Translation/Tafsir selection and attribution.
- Audio playback, repeat, download and offline playback.
- Bookmarks, progress and persistence.
- Prayer times, Adhan and Qibla.
- Hadith, duas and library.
- Registration, login, recovery, roles and admin permissions.
- Database records, uploaded files and user associations.
- Responsive phone layout, accessibility, loading/empty/error/offline states.

Test automated and manually on desktop and real mobile devices. Verify Arabic fonts, line breaks and diacritics.

## Phase E — GitHub and deployment
1. After import, connect Lovable to GitHub using its Git integration. It may create a new repository; do not assume it can attach to any existing repository.
2. Keep Bolt source/export archived separately.
3. Designate one sync branch and avoid simultaneous edits in Lovable and external tools.
4. Keep secrets in provider secret stores.
5. Deploy to staging first.
6. Test auth, database, content, audio, offline and admin flows.
7. Switch production domain only after owner approval and rollback planning.
8. Keep old deployment/database backups.

## Data/account warning
A code ZIP does not automatically include live database rows, user accounts, uploaded files, passwords, active sessions or service secrets. These may require separate exports and migration. Passwords and active sessions should not be assumed portable; plan account recovery/password reset if needed.

## Credit caution
Lovable's official import page currently advertises one eligible first import free until a working preview; later edits and further imports use normal credits. Check the actual account's import dialog and offer status before relying on it. Do not repeatedly import the same project.

## Stop conditions
Stop before destructive changes if the export is incomplete, database/auth ownership is unclear, a migration could overwrite data, Quran content provenance is unknown, or production settings/domain/payment integrations would change.

## Completion criteria
A dated source backup, clean import, verified database mapping, secrets configuration, passing critical tests, tested RTL/mobile/offline behavior, secure admin permissions, staging deployment and owner-approved production switch.