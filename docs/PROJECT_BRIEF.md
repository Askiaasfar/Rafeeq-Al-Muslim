# RAFEEQ AL-MUSLIM — PROJECT BRIEF AND JOURNEY

## Identity and name history
The project began as **Nur Al-Quran**, a complete Quran and Islamic platform vision, not merely a reader. **SIRAJ** was later proposed as a working name. **RAFEEQ AL-MUSLIM / RAFEEQ** was subsequently proposed as the brand direction. The current GitHub repository and user-provided Bolt project use Rafeeq Al-Muslim. Do not invent a formal approval date for earlier proposed names.

## User's core direction
- Build a legitimate, trustworthy Islamic learning and guidance platform.
- Deliver a polished, phone-first web experience and an Android APK/app path.
- Earlier rebuild discussions preferred Replit; the latest explicit direction is to continue the existing Bolt project using Lovable because waiting for Bolt credits is interrupting progress.
- Fix existing errors and weaknesses; do not throw away working functionality or blindly rebuild.
- Core Quran reading and essential resources should work offline wherever technically and legally possible.
- Keep owner/admin capabilities private and protected.
- Islamic accuracy is more important than feature count or visual polish.

## Recovered feature scope
### Quran reader
- Complete Quran: 114 Surahs; original scope referenced 604 Madani Mushaf pages.
- Correct Uthmani Arabic script, diacritics, verse numbering, page mapping and RTL.
- Surah, Juz, page and ayah navigation.
- Translations and Tafsir with named translator/scholar, edition, source and language metadata.
- Search, bookmarks, last-read position, reading history and progress.

### Recitation
- Audio playback, repeat Surah/ayah/range, reciter and riwayah metadata.
- Downloadable audio for offline listening, with storage management and integrity checks.
- Never label a recitation with an unsupported reciter or riwayah.

### Tajweed and learning
- Tajweed rules and guided learning.
- AI-assisted recitation feedback was discussed as a possible advanced feature, not a confirmed engine.
- AI feedback must be labelled assistance, not a definitive ruling or substitute for a qualified teacher.

### Worship and resources
- Prayer times and Adhan, with transparent calculation method and user settings.
- Qibla direction with sensor calibration and clear limitations.
- Hadith, duas/adhkar and an Islamic library with source attribution.
- Learning/memorization progress where implemented accurately.

### Offline-first
- Quran text, selected translations, bookmarks and reading position should work offline.
- Audio and large resources must be explicitly downloaded with progress, cancellation/resume, storage estimates and integrity checks.
- Clearly distinguish downloaded content from online-only content.
- Sync and advanced AI may require connectivity; communicate this honestly.

### Administration
- Protected owner/admin dashboard and content management.
- Server-side authorization and audit logs.
- Hiding a button in the UI is not sufficient security.

## Recovered journey
- **2026-11-07:** User described the Nur Al-Quran vision as a full platform: Quran, recitation/riwayah, Tajweed teacher, prayer/Adhan/Qibla, library and progress.
- **2026-11-07:** User requested a legitimate Islamic guidance APK and website, mostly offline, with previous errors fixed. Replit was preferred then.
- **2026-11-07:** SIRAJ name and an Expo/React Native + TypeScript + Node + PostgreSQL + SQLite architecture were proposed. These were assistant proposals, not verified implementation decisions.
- **2026-11-10:** RAFEEQ AL-MUSLIM / RAFEEQ branding was proposed with Quran, prayer, Qibla, Tajweed, Hadith, duas, library, offline downloads and private admin.
- **2026-11-12:** User reinforced a preference for a polished phone-first UI, disliking a newspaper/report-like layout that does not fit a phone.
- **2026-11-24:** User supplied the Bolt project link and said they intend to continue in Lovable because Bolt credits take too long to refresh. The Rafeeq GitHub repository was found with only a placeholder README at initial inspection. Bolt source has not yet been imported or verified.

## Confirmed vs proposed vs unknown
**Confirmed:** user vision, core scope, current intention to continue Bolt project with Lovable, existence of Rafeeq GitHub repository.
**Proposed:** tagline, Expo/React Native, React Native Web, Node/TypeScript, PostgreSQL, SQLite, specific content APIs and AI provider.
**Unknown:** actual Bolt code, routes, errors, backend, database, auth, storage, content corpus, recitation, offline behavior, APK, deployment and admin workflows.

## Product principles
- Accuracy before novelty.
- Quran text is immutable canonical content from a verified source; never generate scripture with an LLM.
- Display provenance for translations, Tafsir, Hadith and recitation.
- Label AI explanations and uncertainty.
- Offline means tested offline, not a badge.
- Privacy and server-side authorization are mandatory.
- Do not claim completion without end-to-end evidence.