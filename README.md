# Google review outreach

This repo has:

- `MESSAGE.md` — the Google review outreach message and bare-bones drafting rules.
- `data/gmail_accounts.txt` — the seven Gmail accounts and their GitHub Actions secret-name mapping, copied from `agads007-sys/outreach-barebones`.

For each new prospect: find an appropriate official contact, lightly personalize `MESSAGE.md`, and create a Gmail draft only.

When multiple connected Gmail accounts are available, spread genuinely new drafts across the seven accounts in `data/gmail_accounts.txt`. Do not duplicate prospects just to fill accounts.

The Gmail mapping uses `GMAIL1_APP_PASSWORD` through `GMAIL7_APP_PASSWORD`. Actual app-password values must stay in GitHub **Settings > Secrets and variables > Actions** and must never be committed to the repository.

**Never send automatically.**
