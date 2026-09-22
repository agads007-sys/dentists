# Message

## NON-NEGOTIABLE: SAME MESSAGE, DIFFERENT WORDING

Every dentist draft must communicate the SAME message below.

"Variation" means PARAPHRASE, not a new pitch.

Think of it like this:
- "Huset brænder."
- "Huset står i flammer."
- "Der er ild i huset."

Different words. Same message.

That is exactly how these emails must vary.

Do NOT merely swap one or two synonyms while copying the rest word-for-word. Rewrite sentences naturally and substantially, while preserving every important idea, the same conviction, the same sequence of reasoning, and the same offer.

Do NOT invent new angles, clinic-history stories, marketing arguments, benefits, objections, or sales logic.

## The message that every email must preserve

1. Michael came across the clinic on Google / while looking at dentists.
2. State the clinic's VERIFIED current Google review count.
3. Michael compared the clinic with other dentists in the area and genuinely believes there is a lot of opportunity in getting more reviews.
4. Explain the reason plainly: people looking for a dentist compare clinics on Google, and a large difference in review count matters when choosing between clinics.
5. "Det er derfor, jeg skriver" / a natural paraphrase carrying exactly that meaning.
6. Explain the product: after a patient visit, the clinic enters the patient's phone number. The patient gets an SMS with a direct link to the clinic's Google profile/review page and can leave a review immediately.
7. Explain that this takes almost no time for the clinic, but doing it consistently with patients can make a major difference to how the clinic looks on Google over time.
8. Michael sets everything up and handles it.
9. Price is exactly 299 kr. per month.
10. No binding.
11. Say naturally that Michael thinks it would be very relevant / obvious for this clinic.
12. End with a short conversational CTA asking whether they want to see it / whether it could be relevant.
13. Sign "Mvh\nMichael".

Every draft must preserve ALL of those points. A draft that omits one of the core points in order to be "different" is wrong.

## Master reference

Hej

Jeg faldt lige over jer på Google og så, at I har [X] anmeldelser.

Jeg sammenlignede jer lige med nogle af de andre tandlæger i området, og helt ærligt tror jeg, der er virkelig meget at hente her.

Når folk skal finde en ny tandlæge, sidder de jo og kigger på Google. Og hvis de står mellem to klinikker, hvor den ene har 15 anmeldelser og den anden har 150, så betyder det altså noget.

Det er derfor, jeg skriver.

Jeg har lavet noget ret simpelt, hvor I efter et besøg bare taster patientens telefonnummer ind. Så får de en SMS med et link direkte til jeres Google-profil, og så kan de give jer en anmeldelse med det samme.

Det tager jer nærmest ingen tid, men hvis I gør det fast med jeres patienter, tror jeg seriøst, det kan gøre en kæmpe forskel for, hvordan I ser ud på Google over tid.

Jeg sætter det hele op og står for det. 299 kr. om måneden, ingen binding.

Synes faktisk, det ville være oplagt hos jer.

Skal jeg vise jer det?

Mvh
Michael

## What good variation looks like

A new draft may say:

"Jeg sad lige og kiggede på tandlæger på Google og faldt over jer. I ligger på [X] anmeldelser lige nu."

Another may say:

"Jeg så lige jeres klinik på Google og lagde mærke til, at I har [X] anmeldelser."

Another may say:

"Jeg var inde og kigge på tandlæger i området og endte på jeres Google-profil. I har [X] anmeldelser lige nu."

Those are genuinely different sentences carrying the exact same message.

The same principle applies to EVERY paragraph.

For the comparison/reasoning paragraph, examples of the same message include:

"Jeg kiggede også på nogle af de andre tandlæger omkring jer, og jeg tror virkelig, der er meget at hente. Folk sammenligner jo klinikker på Google, og hvis én har langt flere anmeldelser end en anden, så spiller det selvfølgelig ind."

or:

"Da jeg sammenlignede jer med de andre klinikker i området, tænkte jeg med det samme, at der ligger en ret stor mulighed her. Når folk leder efter en ny tandlæge, bruger de Google til at sammenligne, og forskellen på få og mange anmeldelser betyder altså noget."

Same meaning. Different wording.

Do this throughout the entire email.

## Variation requirements across a batch

Do not create a batch where 20 emails are 90% identical.

Across a batch:
- Rewrite the opening in multiple genuinely different ways.
- Rewrite the local-comparison paragraph in multiple genuinely different ways.
- Rewrite the explanation of why reviews matter in multiple genuinely different ways.
- Rewrite the SMS-system explanation in multiple genuinely different ways.
- Rewrite the "almost no work / big difference over time" point in multiple genuinely different ways.
- Rewrite the setup/price/no-binding sentence in multiple genuinely different ways.
- Vary the final conviction sentence.
- Vary the CTA.

But ALWAYS preserve the same message and all 13 core points above.

Do not add random personalization just to make an email different. The variation should primarily come from language.

## Important rule about numbers

[X] MUST be the clinic's verified current Google/Google Maps review count.

The "15 anmeldelser vs 150" sentence in the reference is an illustrative example of why review count matters. It is NOT automatically a factual statement about the clinic's local competitors.

You may paraphrase it generically:
"den ene har langt flere anmeldelser end den anden"
"der er stor forskel på antallet af anmeldelser"
"den ene har fået bygget markant flere anmeldelser op"

If you use actual competitor numbers as a factual local comparison, verify them first.

## Tone

Write like Michael would actually speak on a phone call.

Casual. Direct. Confident. Conversational. High conviction.

Do not weaken the pitch to sound casual.

Avoid corporate/template language, polished agency copy, unnecessary headings inside the email, colons, dashes, or wording that sounds AI-generated.

Do not use timid filler.

Do not make guaranteed results or unsupported performance claims.

## Personalization

The verified Google review count is the primary personalization.

A second verified clinic-specific fact is optional and should only be used if it fits naturally without changing the message. Never turn the email into a story about the clinic.

Never invent details.

## Operational rules

- DRAFTS ONLY. NEVER SEND AUTOMATICALLY.
- Use an appropriate officially published email/contact route.
- For dentist/dental-clinic prospects, verify the current Google/Google Maps review count before drafting.
- Only use clinics with fewer than 30 Google reviews. Skip clinics with 30 or more.
- Never guess a review count.
- At the start of each run, load `data/excluded_emails.txt`, `data/excluded_facilities.txt`, and `data/exclusions-log.txt` once and use them as the working dedup list for the whole run.
- These Dentist exclusions are campaign-specific. Do not use exclusion lists from `agads007-sys/outreach-barebones` or another campaign.
- Never reuse a listed email or facility.
- Keep every newly selected prospect in the working dedup list during the run.
- After successful new drafts are created, append all new emails and facilities to `data/exclusions-log.txt` in one update.
- Spread new drafts across all seven Gmail accounts listed in `data/gmail_accounts.txt`; do not duplicate prospects merely to fill accounts.
