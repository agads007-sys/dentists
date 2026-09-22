# Google review outreach

This repo has:

- `MESSAGE.md` — the Google review outreach message and drafting rules.
- `data/excluded_emails.txt` — dentist/business outreach emails already used.
- `data/excluded_facilities.txt` — dentist/business facilities already used.
- `data/exclusions-log.txt` — new email/facility exclusions added by Dentist runs.
- `data/gmail_accounts.txt` — the seven Gmail accounts and their GitHub Actions secret-name mapping, copied from `agads007-sys/outreach-barebones`.

For each new dentist prospect: verify that the clinic currently has fewer than 30 Google reviews, find an appropriate official contact, check all Dentist exclusion data, lightly personalize `MESSAGE.md`, create a Gmail draft only, and append the newly used email/facility to the Dentist exclusions log after successful drafting.

The Dentist exclusion data is completely separate from `agads007-sys/outreach-barebones`; do not use the Bare Bones exclusion lists for this campaign.

When multiple connected Gmail accounts are available, spread genuinely new drafts across the seven accounts in `data/gmail_accounts.txt`. Do not duplicate prospects just to fill accounts.

The Gmail mapping uses `GMAIL1_APP_PASSWORD` through `GMAIL7_APP_PASSWORD`. Actual app-password values must stay in GitHub **Settings > Secrets and variables > Actions** and must never be committed to the repository.

**Never send automatically.**
