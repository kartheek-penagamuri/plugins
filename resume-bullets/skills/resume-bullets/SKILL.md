---
name: resume-bullets
description: Turn a career "brain dump" of projects, roles, and contributions into strong, impact-first resume bullet points, or review, critique, and tighten career, resume, LinkedIn, or professional-experience bullets the user already has. Use this whenever someone shares an unstructured account of what they worked on and wants resume material, career bullets, or help describing their professional experience, even if they do not say the word "resume", and also whenever they ask to review, rephrase, or improve existing career/resume bullets. Do not format a full resume; produce the bullets.
---

# Resume Bullets

Take a messy brain dump of someone's work and return sharp bullet points they can drop into a resume, or, when they arrive with bullets already drafted, audit and tighten those. Your job is the wording of the bullets, not layout, fonts, or a finished document.

## Two modes

**Generate** - the input is an unstructured account of work. Produce bullets from scratch using the rules below.

**Review / revise** - the input is existing bullets, such as a pasted list, a file, or a previous draft. Audit each bullet against the rules below; report the violations if the user asked for a review, rewrite them if they asked for fixes. When the user brings new material in a later round, check it against bullets already produced in the conversation. The same accomplishment often resurfaces with different wording, and it must never appear as two bullets. Merge into the stronger version instead.

## The one thing that matters: lead with impact

A resume is skimmed in about 15 seconds. The reader wants results, not duties. Every bullet leads with the outcome, then explains how it was achieved.

**Structure:** `[Impact / result] by [what you did and how]`

- Weak: Responsible for the checkout service.
- Weak: Rewrote the checkout service in Go.
- Strong: Cut checkout latency 40% and eliminated Black Friday outages by rewriting the payment service in Go with async retries.

Start completed accomplishments with a strong past-tense action verb, such as Cut, Led, Shipped, Designed, Automated, or Grew. For ongoing responsibilities in a current role, use present tense only when the work is still active. Keep each bullet under about 30 words. One bullet per accomplishment; do not split the same win across two bullets.

## Not everything earns a bullet

A skimming recruiter averages the bullets they read, so weak ones drag down strong ones. Lead each role with the 2-3 items that carry real weight. Routine work, such as fixing bugs, doing code reviews, or attending design discussions, only gets a bullet if it produced a distinct result. Otherwise fold it into a stronger bullet or drop it. If the user has little else, keep such an item but mark it in the notes as a candidate to cut.

## Quantify, but never invent numbers

Numbers make impact legible: latency, revenue, users, percentages, time saved, team size, scale, QPS, rows, dollars. Mine the brain dump for anything measurable and surface it.

When the impact is real but the number is missing, do not fabricate one. Unless the user explicitly asked for coaching or questions, do not stop to interview them; write the bullet with a clear placeholder like `[X%]` or `[$X]`, then add a brief note asking them to verify or replace it.

Two limits keep this honest and readable:

- Placeholders are for missing numbers on impact the user actually described. Do not invent the impact claim itself and leave the number blank.
- Cap placeholders at 2-3 total, on the bullets where a number matters most. For the rest, write the strongest honest bullet without a number.

## Honesty beyond the numbers

Fabrication is not only made-up metrics. Watch for these failure modes:

- **Unrealized outcomes.** A prototype, proposal, or POC that never shipped did not achieve its intended outcome; it targeted or demonstrated it. The award, pilot, leadership buy-in, or projected result may be claimable.
- **Ambiguous metrics.** "Raised attendance 80%" could mean raised by 80% or raised to 80%. Flag ambiguous metrics rather than silently picking one.
- **Inferred impact.** If the user described building a dashboard but never said forecasts got more accurate, "improving forecast accuracy" is an inference. Ask or flag it as unverified.

## Write for the skimming stranger

- Bullets are read by recruiters, HR screeners, and often non-native speakers, not domain insiders.
- Prefer plain words: "unplanned absences" over "ad hoc leave." Expand acronyms on first use unless universally known, such as API or SQL.
- Internal team names, codenames, and company jargon mean nothing outside the company; translate them.

## Read between the lines

Brain dumps bury the good stuff in casual phrasing. "I ended up owning the migration because no one else would" is initiative and ownership. "Helped the new hires get ramped up" is mentorship. Pull the latent accomplishment out; do not just transcribe.

## Role emphasis

**Software Engineer** - technical depth is the point. Name the hard problem, the scale, and the measurable result. Concrete tech and systems belong here.

**Program / Product Manager** - show enough technical depth to be credible, but lead with planning, design, cross-team coordination, and initiative. Keep big-company work light on implementation detail. Actively look for and elevate:

- self-driven projects, tools, or communities the user built and ran;
- organizing large events;
- teaching, mentoring, or training roles.

These often live outside the job section of a brain dump; do not let them get lost.

**Any other role** - follow the PM emphasis: lead with outcomes, ownership, and initiative rather than implementation detail, and quantify scale wherever the material allows.

## Output

Produce grouped bullet lists only.

- Use light group labels for roles, companies, projects, or a final `Notes` group.
- In generate mode, return polished bullets under their relevant groups.
- In review mode, return the rewritten bullets first. Add a `Notes` group only for changed-because explanations, placeholders, ambiguous metrics, unverified claims, or candidate-to-cut bullets.
- Keep notes brief and bullet-shaped; do not add prose summaries, resume layout, or full-document formatting.
