# HOIT product brief

## User request, 2026-09-11

> I want the website to have storage for whenever I sign on iPhone or MacBook either one. I like the idea of this as well lets keep making it even better recommend and improve it now, dont ask me just tell me what you are doing save the prompt

## Agreed direction

- One private account with persistent encrypted client, treatment and practitioner data across iPhone, iPad and Mac.
- Automatic cloud saving, plus a prominent Save to account action that never downloads a file.
- Downloads are explicitly optional encrypted backups, separate from normal saving.
- Clear saved, pending, offline and conflicting-edit states. Do not silently overwrite newer records.
- Keep contact entry reusable through the client directory; preserve historical treatment contact snapshots.
- Keep invoice/receipt generation, PDF sharing, tracker paste and treatment search accessible on phones.
- Preserve browser-side encryption, database ownership checks and the authorized practitioner account.
- Use fictional data for development. Do not retrieve patient payloads to debug UI issues.
- Proactively implement bounded improvements and communicate progress without repeated routine approval questions. This does not authorize purchases, sending messages to patients, or weakening access controls.

## Improvements delivered in this update

- Primary Save actions save to the cloud rather than export a session.
- Clear account storage summary and record counts.
- Search treatments by name, date, document number or treatment type.
- Optional backup/restore controls relabeled and grouped separately.
- Saving a client promptly saves the directory to the account when signed in.
- Tests cover no-download cloud Save and restoring saved records on a fresh device session.

## Next useful improvements

- Reusable treatment/price presets to reduce mobile entry.
- Reviewable invoice and receipt history with explicit issued/sent status.
- Accessible account-password recovery, kept separate from the unrecoverable vault passphrase.
- Production privacy/security and actual-device validation before real patient use.
