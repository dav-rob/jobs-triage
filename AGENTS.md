Read the job advert and explain it to me as though we're chatting in a pub.

Tell me:

• what the company appears to do (and provide a little background if it isn't obvious from the advert)

• what problem they're actually trying to solve

• what kind of person they really seem to want

• what the day-to-day reality of the role is likely to be

• how much management-speak, corporate theatre, or aspirational nonsense is present

• whether there are any red flags

• whether the environment feels grounded, political, chaotic, bureaucratic, startup-ish, excessively process-driven, unusually healthy, or something else

• whether somebody who values independent thinking, systems thinking, curiosity, and good judgement would likely thrive or become frustrated there

Don't rewrite the advert.

Translate it into ordinary English.

Keep it conversational and balanced.

Two or three paragraphs maximum.

If the advert gives clues about company culture, tell me what they are.

If you think the advert is hiding something, say so.

If the advert appears unrealistic, contradictory, or overloaded with buzzwords, point that out.

Do not assume the company is healthy or unhealthy. Explain what evidence you are using.

I am not trying to decide whether the company is good or bad. I am trying to understand what sort of environment it actually is and what sort of person is likely to succeed there.

The tone of the summary is the most important thing. Everything else is secondary.

Example style:

"This looks like a medium-sized insurance company trying to modernise a legacy estate. They want someone senior enough to make architectural decisions but practical enough not to disappear into PowerPoint. The advert contains the usual 'fast-paced environment' language but doesn't feel particularly cultish. The tone is fairly grounded and they seem mainly worried about integrating a lot of existing systems rather than building something radically new.

The ideal candidate appears to be somebody who has spent years navigating messy organisations, can talk to both engineers and managers, and isn't precious about technology choices. They mention AWS repeatedly but the real requirement is systems thinking.

My sense is that this is a relatively ordinary professional environment rather than a startup trying to change the world. Some management-speak is present but not excessive."

---

## Batch mode (no URL in the prompt)

If I don't give you a URL in my message, check for a file at:

./job-urls.txt

If the file exists and contains URLs, process them one at a time:
1. Take the first URL in the file.
2. Follow the normal workflow below to produce a summary file.
3. Once the summary file is saved, delete that URL from job-urls.txt.
4. Move on to the next URL and repeat until the file is empty.

If the file doesn't exist or is empty, let me know and stop.

---

## Getting the job description

Try to read the URL directly. If it works, use that.

If the URL is blocked (403, redirect wall, login required, etc.):
1. Stop and ask me to paste in the job description.
2. Once I paste it, write your summary based on that text only.
3. Optionally do a quick web search to fill in any background on the company, but do not let that override what I pasted. The pasted text is the source of truth.

---

## Saving the summary

Create a .txt file in the summaries folder.

Filename: job title - company.txt

The file must follow this exact structure:

Title: [job title]
Company: [company name]
URL: [the URL I gave you]
Original Source: search for "[job title]" "[company name]"

Summary:
[Your 2-3 paragraph summary]

---

Original text:
[Paste the full job description text here, exactly as I gave it to you]

---

Notes:
- Do not include salary information.
- Keep the summary conversational. That is the point of this whole exercise.
- The "Original Source" field is just a search hint for future reference, not a verified URL. Write it as a search query, e.g.: search for "Engineering Manager" "Just Group"
- The "Original text" section goes at the very bottom, after the summary.
