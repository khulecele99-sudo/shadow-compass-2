# ShadowCompass — Echo first test build

## What is included
- Echo conversation screen with Guided Reflection and Open Conversation modes.
- Situation, experience-statement, and perspective selection.
- Local-first response logic for this first test build (not a live AI model).
- Existing seven-shape Sonar, results, exercises, journal, and FAQ retained.
- PWA manifest, icons, and service worker for browser installation/offline shell caching.

## Test locally
Open `index.html` in a modern browser. For service-worker/PWA testing, serve the folder over localhost (for example `python -m http.server 8080`) and visit `http://localhost:8080`.

## Publish on GitHub Pages
Upload the contents of this folder to the repository root on the `main` branch. Ensure `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, and `icon-512.png` are all at the root. Then enable GitHub Pages from `main` / root.

## Privacy and limitations
This version does not send Echo messages to an AI provider. Conversation text is held in the page memory only and is not saved to the journal. The existing journal remains local in IndexedDB. Do not add private API keys to this public repository. A secure server-side AI connection is a later stage.

The seven-shape framework is a self-reflection framework, not a validated psychological assessment, diagnosis, or treatment. Exercises should be comfortable; stop if dizzy or distressed.
