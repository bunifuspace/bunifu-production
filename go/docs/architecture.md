# Architecture

- `index.html`: semantic app shell and views.
- `css/app.css`: Apple-inspired responsive visual system.
- `js/app.js`: navigation, UI rendering, form workflows, financial calculations and backup/restore.
- `js/db.js`: IndexedDB schema and transaction-safe CRUD helpers.
- `service-worker.js`: same-origin app-shell cache.

IndexedDB is the source of truth for this single-device build. Cloud synchronization is intentionally not simulated. Future Firebase sync should use per-user UID paths, strict Firestore/Storage rules, unique operation IDs, and an idempotent queue. Financial values are integer TZS.
