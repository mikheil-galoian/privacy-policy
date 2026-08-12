# Privacy Policy for Kin

Last updated: August 12, 2026

## What Kin does

Kin is a personal companion app for finances, goals, notes, planning, files, conversations, and optional AI assistance. Features that record, transcribe, translate, or analyze content start only after a user action.

## Data Kin may process

- **Account data:** email address, account identifier, password verifier, and session data.
- **Financial and planning data:** transactions, categories, goals, notes, reminders, calendar-related items, and planned tasks.
- **Assistant data:** messages and the context you choose to provide.
- **Recordings:** audio you choose to record, transcription status, and transcript.
- **Translation data:** audio, recognized text, translated text, language, and selected voice.
- **Files:** files you choose to add and extracted content when you ask Kin to read them.
- **Diagnostics:** limited crash and operational data used to keep Kin working.

Kin does not use this data for cross-app tracking, does not show third-party advertising, and does not sell personal data.

## Your data-region choice

Kin asks you to choose a data region. A device-region recommendation is only a recommendation; changing the interface language does not move data. Kin records the explicit choice and does not silently fall back to another region when a requested regional service is unavailable.

### Russian data region

When you explicitly choose the Russian data region, **Yandex Cloud** processes and stores:

- email account and session data;
- salted password verifiers, private backups, financial and planning data;
- user files and recorded audio;
- Yandex SpeechKit transcription jobs, status, and transcripts;
- assistant messages and selected context processed by Yandex AI Studio;
- text and selected voice processed by Yandex SpeechKit when you request spoken assistant playback;
- quota counters and redacted operational audit events.

Raw passwords and raw session tokens are not stored. Password verifiers use a salted one-way derivation, and only a hash of the session token is retained on the server.

Global Anthropic assistant processing and Google voice services are disabled in the Russian data region. In that region, requested assistant replies use Yandex AI Studio and requested spoken assistant playback uses Yandex SpeechKit. Kin does not silently send those requests outside the selected region. Google voice translation remains unavailable in the Russian region until a Russian translation provider is connected and disclosed.

### Global data region

When you explicitly choose the global data region, Kin may use:

- **Supabase** for authentication, database, synchronization, server functions, and storage;
- **AssemblyAI** for transcription of recordings you choose to submit;
- **Anthropic** for assistant messages and the transcript or extracted file context you ask the assistant to analyze;
- **Google Cloud Speech-to-Text, Cloud Translation, and Cloud Text-to-Speech** for voice recognition, translation, spoken translation, and selected spoken assistant playback you request.

These providers receive only the data needed for the requested feature. Google Cloud Speech data logging is disabled for Kin's project. Processing may occur outside your country of residence.

## Consent and recording notice

Before first use of cloud recording/transcription, file processing, AI processing, or cloud voice services, Kin presents a consent notice naming the processor for the selected data region. You may decline and continue using features that do not need that processing.

Recording never starts by itself. It begins after you tap the recording control or launch a Kin shortcut. Kin announces the recording aloud before the microphone starts. Record only when participants do not object and follow the laws that apply where you are.

## Retention

For the Russian data region:

- recording audio is automatically deleted after 7 days;
- account sessions and redacted audit events are deleted after 30 days;
- transcripts, files, financial/planning data, messages, and backups remain until you delete them, delete the relevant item, or delete your account.

For the global data region, AssemblyAI recording audio is deleted after 7 days. Other account content remains until you delete it or delete your account, subject to limited operational backups and legal or security obligations.

## Deleting data

You can delete individual supported items in Kin. **Settings -> Delete account** deletes the selected-region cloud account and associated content and clears personal data stored locally by Kin. Account deletion cannot be undone. You may also contact us for a privacy request.

## Security

Kin uses HTTPS encryption in transit, private storage, owner-derived storage paths, short-lived signed file links, device Keychain storage for sessions, least-privilege service permissions, and redacted operational logs. No transmission or storage method can be guaranteed completely secure.

## Children

Kin is not intended for children under 13 and is not designed to knowingly process their personal data.

## Changes

If this policy changes, this page and the date above will be updated.

## Contact

Privacy questions or requests: mgaloyan79@gmail.com
