# Message

Write these emails like a real person who has just noticed a genuine opportunity for the clinic and decided to tell them about it.

The tone should be casual, direct, confident, and conversational. The message should have strong conviction about why Google reviews matter, without sounding like corporate sales copy, a marketing agency, or an automated outreach template.

Do not weaken the pitch just to make it casual. The point is: this is a very simple thing for the clinic to do, but consistently asking real patients for reviews can make a big difference to how the clinic looks when potential patients compare dentists on Google.

Do not make unsupported promises, guaranteed results, or invented numbers. Strong language such as "jeg tror virkelig, det kan gøre en stor forskel" is fine; claims such as "det vil 10x jeres omsætning" are not.

## Core idea

The email should naturally communicate these points, but it does NOT need to use the same sentences or exact paragraph structure every time:

- Michael found the clinic while looking at dentists / Google.
- Mention the clinic's VERIFIED current Google review count naturally.
- Where appropriate, mention that other dentists in the area have considerably more reviews. Do not invent a comparison; verify it first.
- Explain why this matters in normal human language: prospective patients compare clinics online, and Google reviews are an obvious part of what they see.
- Michael has built a simple system for making it much easier to ask existing patients for a review.
- After a visit, the clinic enters the patient's phone number. The patient receives an SMS with a direct link to the clinic's Google profile/review page and can leave a review.
- Michael handles setup and keeps it running.
- Price: 299 kr. per month.
- No binding / no contract commitment.
- End with a short, natural question about whether it could be relevant or whether they want to see it.

## Tone

Write the way Michael could realistically explain the idea on a phone call.

Good:
- "Jeg faldt lige over jer på Google..."
- "Jeg sammenlignede jer lige med nogle af de andre tandlæger i området..."
- "Helt ærligt tror jeg, der er virkelig meget at hente her."
- "Det er derfor, jeg skriver."
- "Jeg har lavet noget ret simpelt..."
- "Det tager jer nærmest ingen tid..."
- "Jeg tror seriøst, det kan gøre en kæmpe forskel over tid."
- "Synes faktisk, det ville være oplagt hos jer."
- "Skal jeg vise jer det?"

Avoid corporate/template language such as:
- "en enkel løsning, der gør det nemmere..."
- "løbende drift"
- "for en virksomhed som jeres"
- "uden at ændre resten af jeres arbejdsgang"
- "øge jeres digitale synlighed"
- "optimere jeres online tilstedeværelse"
- long, polished marketing explanations
- things like colons, dashes or things that scream AI message

Do not become timid or apologetic. Avoid filler like "jeg ved selvfølgelig ikke, om I går op i det" or language that diminishes the importance of the idea.

## Variation

Do NOT produce 25 near-identical emails with synonyms swapped.

Vary the natural flow from draft to draft. For example, some emails can start with the review count; some with the fact Michael found the clinic while comparing local dentists; some with a real clinic detail before connecting it to the review opportunity.

Vary:
- opening
- paragraph lengths
- how the local comparison is phrased
- how the product is explained
- how the benefit is expressed
- CTA

Keep the same underlying offer and facts.

The emails should feel individually written, not generated from one rigid template.

## Personalization

Use real facts from the clinic's own website or another official source. Do not invent details.

Personalization should be light and relevant. The verified Google review count itself is useful personalization. One additional genuine detail about the clinic can be used when it fits naturally, but do not force a random website fact into every email.

Do not write an analysis of the clinic. Do not compliment them with generic claims you cannot verify.

## Example style

Hej

Jeg faldt lige over jer på Google og så, at I har [X] anmeldelser.

Jeg sammenlignede jer lige med nogle af de andre tandlæger i området, og helt ærligt tror jeg, der er virkelig meget at hente her.

Når folk skal finde en ny tandlæge, sidder de jo og kigger på Google. Og hvis de står mellem to klinikker, hvor den ene har markant flere anmeldelser end den anden, så betyder det altså noget.

Det er derfor, jeg skriver.

Jeg har lavet noget ret simpelt, hvor I efter et besøg bare taster patientens telefonnummer ind. Så får de en SMS med et link direkte til jeres Google-profil, og så kan de give jer en anmeldelse med det samme.

Det tager jer nærmest ingen tid, men hvis I gør det fast med jeres patienter, tror jeg seriøst, det kan gøre en kæmpe forskel for, hvordan I ser ud på Google over tid.

Jeg sætter det hele op og står for det. 299 kr. om måneden, ingen binding.

Synes faktisk, det ville være oplagt hos jer.

Skal jeg vise jer det?

Mvh
Michael

This is an example of the VOICE and level of conviction, not a template to copy sentence-for-sentence.

## Rules

- Drafts only. Never send automatically.
- Keep the same core offer and meaning, but vary the wording and structure naturally from draft to draft.
- Keep the tone human, casual, direct, and confident. Strong conviction is good; corporate sales language is not.
- Do not make guaranteed or unsupported performance claims.
- Personalize using verified real information only.
- Keep it concise. Do not turn personalization into an analysis.
- Use an appropriate official published email/contact route.
- For dentist/dental-clinic prospects, verify the current Google/Google Maps review count before drafting. Only use clinics with fewer than 30 Google reviews; skip clinics with 30 or more.
- Use the VERIFIED review count in the email. Never guess or use an old/unverified count.
- If comparing the clinic's review count with other dentists in the area, verify that comparison rather than assuming it.
- At the start of each run, load `data/excluded_emails.txt`, `data/excluded_facilities.txt`, and `data/exclusions-log.txt` once and use them as the working dedup list for the whole run.
- These Dentist exclusion files are campaign-specific. Do not use exclusion lists from `agads007-sys/outreach-barebones` or another campaign.
- Never reuse a listed email or facility.
- Keep every newly selected prospect in the working dedup list during the run so the same email or business cannot be selected twice in that run.
- After all successful new drafts are created, append all new emails and facilities to `data/exclusions-log.txt` in one update.
- When multiple connected Gmail accounts are available, spread new drafts across all seven accounts listed in `data/gmail_accounts.txt`; do not duplicate a prospect just to fill accounts.
