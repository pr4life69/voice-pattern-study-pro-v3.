# Voice Pattern Study Pro — v3.0 psychology-informed beta

A local-first Progressive Web App for consent-based communication and voice-pattern research.

## Features
- Installable PWA and offline app shell (HTTPS hosting required)
- Multiple participants/aliases, study types, and reusable questions
- Microphone recording, live waveform, estimated fundamental pitch graph, volume level
- Browser speech-to-text where supported; editable transcript
- Local response history, baseline acoustic summary, CSV/JSON export
- Optional participant self-report check-in (calmness, stress, energy, context)
- Psychology-informed, transparent rule-based review prompts and within-person baseline comparisons
- Transcript-derived estimated words per minute
- Psychologist/professional review summary and print-to-PDF

## Important limitations
The psychology-informed review is a transparent local rules engine, not a trained generative AI or validated psychometric instrument. It compares a participant’s measurements with their own baseline and combines them with optional participant self-report. It does not infer emotion, intent, honesty, personality, or mental-health conditions. It generates questions for a qualified human reviewer.

This app provides descriptive acoustic measurements only. It does not detect lies, identify speakers, diagnose mental-health conditions, infer personality, or measure psychological states. Pitch and low-energy frames are affected by content, accent, physiology, room acoustics, microphone placement, and browser/device processing. The baseline view is a simple descriptive reference, not a validated statistical or biometric model. The app does not currently retain audio recordings; it saves derived measurements, transcript, and notes in browser localStorage. Speech recognition may send audio to the browser/platform speech service depending on browser implementation and settings.

Obtain informed consent before recording. Do not record minors or sensitive conversations without appropriate legal authority, consent, and safeguards. Avoid using the app for employment, discipline, diagnosis, law enforcement, or other consequential decisions.

## Publish using GitHub Pages from Android
1. Extract this ZIP on your phone.
2. In GitHub, create a repository named `voice-pattern-study-pro`.
3. Use Chrome (not the GitHub app) to open the repository. Choose **Add file → Upload files** and upload the *contents* of this folder, keeping `css`, `js`, and `icons` folders intact.
4. Commit to `main`.
5. Repository **Settings → Pages → Build and deployment**: choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
6. Wait for deployment. Open `https://YOUR-USERNAME.github.io/voice-pattern-study-pro/` in Chrome. Grant microphone permission. Use Chrome menu → **Add to Home screen** or **Install app**.

Microphone access requires HTTPS or localhost. Browser speech recognition support varies; Chrome Android is recommended. Saved browser data remains on that device/browser and may be cleared by browser storage cleanup. Export backups regularly.
