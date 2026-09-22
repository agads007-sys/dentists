# Message

Keep this exact core message and offer. For each business, vary the wording a little so it sounds natural and personal, but do not change what is being said.

Personalize the two business-specific parts using real facts from the business's own website or another official source. Do not invent details.

## Danish base

Hej

Jeg så, at [BUSINESS-SPECIFIC OBSERVATION].

Jeg har lavet en enkel løsning, der gør det nemmere at bede rigtige kunder om en Google-anmeldelse efter et besøg. En medarbejder indtaster kundens telefonnummer i en enkel webformular, og kunden får virksomhedens Google-anmeldelseslink på SMS.

Jeg står for opsætning og den løbende drift, så det kræver meget lidt arbejde fra jer.

[BUSINESS-SPECIFIC RELEVANCE SENTENCE].

Hvis det lyder relevant, viser jeg gerne kort, hvordan det fungerer.

Mvh
Michael

## Example

Hej

Jeg så, at [BUSINESS] har fokus på [REAL BUSINESS-SPECIFIC DETAIL].

Jeg har lavet en enkel løsning, der gør det nemmere at bede rigtige kunder om en Google-anmeldelse efter et besøg. En medarbejder indtaster kundens telefonnummer i en enkel webformular, og kunden får virksomhedens Google-anmeldelseslink på SMS.

Jeg står for opsætning og den løbende drift, så det kræver meget lidt arbejde fra jer.

For en virksomhed som jeres kan det gøre selve opfølgningen efter et besøg enkel for medarbejderne uden at ændre resten af jeres arbejdsgang.

Hvis det lyder relevant, viser jeg gerne kort, hvordan det fungerer.

Mvh
Michael

## Rules

- Drafts only. Never send automatically.
- Keep the same core message, order, offer, and meaning.
- Lightly vary wording from draft to draft; do not make every email identical.
- Personalize the opening observation and the business-relevance sentence to the actual business.
- Keep it concise and natural. Do not turn personalization into an analysis.
- Use an appropriate official published email/contact route.
- For dentist/dental-clinic prospects, verify the current Google/Google Maps review count before drafting. Only use clinics with fewer than 30 Google reviews; skip clinics with 30 or more.
- At the start of each run, load `data/excluded_emails.txt`, `data/excluded_facilities.txt`, and `data/exclusions-log.txt` once and use them as the working dedup list for the whole run.
- These Dentist exclusion files are campaign-specific. Do not use exclusion lists from `agads007-sys/outreach-barebones` or another campaign.
- Never reuse a listed email or facility.
- Keep every newly selected prospect in the working dedup list during the run so the same email or business cannot be selected twice in that run.
- After all successful new drafts are created, append all new emails and facilities to `data/exclusions-log.txt` in one update.
- When multiple connected Gmail accounts are available, spread new drafts across all seven accounts listed in `data/gmail_accounts.txt`; do not duplicate a prospect just to fill accounts.
