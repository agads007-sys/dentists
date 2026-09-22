# Message

Use the Danish base message below as the actual master message for every dentist outreach draft.

Do NOT reinvent the pitch. Do NOT create a new sales angle for each clinic. Do NOT turn personalization into a paragraph about the clinic.

The drafts should be variations of THIS message, not merely messages inspired by it.

## Danish master message

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

## How to vary it

Keep the message, argument, intensity, offer, and overall flow essentially the same.

Variation means making small, natural changes so the emails do not look copied word-for-word. For example:

- "Jeg faldt lige over jer på Google..." can become "Jeg så lige jer på Google..." or "Jeg sad lige og kiggede på tandlæger i området og faldt over jer..."
- "der er virkelig meget at hente her" can become "I har virkelig meget at hente her" or "jeg tror seriøst, der er meget at hente her"
- The explanation about patients comparing dentists can be phrased slightly differently while keeping the same strong point.
- The explanation of the SMS system can be worded slightly differently, but it must remain just as clear.
- "Skal jeg vise jer det?" can become "Kunne det være noget for jer?" or "Skal jeg lige vise jer, hvordan det fungerer?"

Do not substantially change the structure. Do not invent a different pitch. Do not replace the strong Google-review argument with a clinic-history story or generic personalization.

The goal is that every draft sounds like Michael wrote the same strong message personally to that clinic, with natural wording differences.

## Important rule about numbers

[X] MUST be the clinic's verified current Google/Google Maps review count.

The "15 anmeldelser vs 150" line is an illustration of why review count matters. It is NOT a factual claim about the specific clinic or its competitors.

If wording makes it sound like 15 and 150 are the actual local counts, change it to a generic formulation such as:

"Og hvis de står mellem to klinikker, hvor den ene har markant flere anmeldelser end den anden, så betyder det altså noget."

If you make a factual comparison with actual nearby dentists, verify the comparison first.

## Tone

Casual, direct, confident, conversational and high-conviction.

It should sound like something Michael could genuinely say on a phone call.

Casual does NOT mean timid. Do not weaken the importance of Google reviews. The message should make it clear that this is a simple thing for the clinic to do and that Michael genuinely believes consistently getting more real patient reviews can make a major difference to how the clinic looks when potential patients compare dentists on Google.

Avoid corporate/template language such as:

- "en enkel løsning, der gør det nemmere"
- "løbende drift"
- "for en virksomhed som jeres"
- "uden at ændre resten af jeres arbejdsgang"
- "øge jeres digitale synlighed"
- "optimere jeres online tilstedeværelse"
- long polished marketing explanations
- unnecessary colons, dashes, headings or other things inside the email that make it look AI-generated

Avoid timid filler such as "jeg ved selvfølgelig ikke, om I går op i det."

Do not make guaranteed performance claims or invented numerical results.

## Personalization

Keep personalization light.

The verified Google review count is the main personalization.

A second real clinic-specific detail may be used only if it fits naturally into the master message without changing the pitch. Do not force a random fact from the clinic website into the email.

Never invent details.

## Rules

- Drafts only. Never send automatically.
- Use the Danish master message above as the base for every draft.
- Vary wording naturally, but stay close to the master message.
- Do not create completely different structures or sales angles just for variation.
- Keep the same strong argument about why Google reviews matter.
- Keep the same product explanation.
- Price is 299 kr. per month.
- No binding.
- Keep the CTA short and conversational.
- Personalize using verified real information only.
- Keep it concise and human.
- Use an appropriate official published email/contact route.
- For dentist/dental-clinic prospects, verify the current Google/Google Maps review count before drafting. Only use clinics with fewer than 30 Google reviews; skip clinics with 30 or more.
- Use the VERIFIED review count in the email. Never guess or use an old/unverified count.
- If comparing the clinic's review count with other dentists in the area as a factual claim, verify that comparison rather than assuming it.
- At the start of each run, load `data/excluded_emails.txt`, `data/excluded_facilities.txt`, and `data/exclusions-log.txt` once and use them as the working dedup list for the whole run.
- These Dentist exclusion files are campaign-specific. Do not use exclusion lists from `agads007-sys/outreach-barebones` or another campaign.
- Never reuse a listed email or facility.
- Keep every newly selected prospect in the working dedup list during the run so the same email or business cannot be selected twice in that run.
- After all successful new drafts are created, append all new emails and facilities to `data/exclusions-log.txt` in one update.
- When multiple connected Gmail accounts are available, spread new drafts across all seven accounts listed in `data/gmail_accounts.txt`; do not duplicate a prospect just to fill accounts.
