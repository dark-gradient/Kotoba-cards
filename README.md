# Kotoba Cards

A separate, offline-first Japanese vocabulary discovery notebook for words encountered in listening practice, mock tests, videos, reading and conversations. Not a fixed vocabulary curriculum or a replacement for Minna Kotoba.

## MVP
- Quick capture with source, title, timestamp/question and original context
- Searchable personal word list
- ChatGPT prompt generation; paste the explanation back into the app
- IndexedDB local persistence and JSON backup export/import
- Installable PWA manifest and service worker
- No backend, login or API key required

## Deploy
Static site: no build command; serve repository root. Service workers require HTTPS or localhost. On iPhone, open the HTTPS URL in Safari and choose Share → Add to Home Screen.

## AI and privacy
The app does not call an AI API directly. You choose what to paste into ChatGPT. Entries are stored locally in IndexedDB and do not sync between devices. Export backups regularly.