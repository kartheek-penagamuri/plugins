---
name: resume-bullets
description: Turn a career "brain dump" of projects, roles, and contributions into strong, impact-first resume bullet points — or review, critique, and tighten resume bullets the user already has. Use this whenever someone shares an unstructured account of what they've worked on and wants resume material, bullets, or help describing their experience — even if they don't say the word "resume" — and also whenever they ask to review, rephrase, or improve existing bullets. Do NOT format a full resume; produce the bullets.
---

# Resume Bullets

Take a messy brain dump of someone's work and return sharp bullet points they can drop into a resume — or, when they arrive with bullets already drafted, audit and tighten those. Your job is the *wording of the bullets*, not layout, fonts, or a finished document.

## Two modes

**Generate** — the input is an unstructured account of work. Produce bullets from scratch using the rules below.

**Review / revise** — the input is existing bullets (a pasted list, a file, a previous draft). Audit each bullet against the rules below; report the violations if the user asked for a review, rewrite them if they asked for fixes. When the user brings new material in a later round, check it against bullets already produced in the conversation — the same accomplishment often resurfaces with different wording, and it must never appear as two bullets. Merge into the stronger version instead.

## The one thing that matters: lead with impact

A resume is skimmed in ~15 seconds. The reader wants results, not duties. So every bullet leads with the outcome, then explains how it was achieved.

**Structure:** `[Impact / result] by [what you did and how]`

- Weak (responsibility): *Responsible for the checkout service.*
- Weak (task, no result): *Rewrote the checkout service in Go.*
- Strong (impact-first): *Cut checkout latency 40% and eliminated Black Friday outages by rewriting the payment service in Go with async retries.*

Start with a strong past-tense action verb (Cut, Led, Shipped, Designed, Automated, Grew). Keep each bullet under ~30 words — a bullet that reads like a paragraph gets skipped, and a hard cap catches bloat that "one or two lines" lets through. One bullet per accomplishment; don't split the same win across two bullets.

## Not everything earns a bullet

A skimming recruiter averages the bullets they read — weak ones drag down strong ones. Lead each role with the 2-3 items that carry real weight. Routine work (fixed bugs, did code reviews, attended design discussions) only gets a bullet if it produced a distinct result; otherwise fold it into a stronger bullet or drop it. If the user has little else, keep such an item but mark it in the notes as a candidate to cut.

## Quantify — but never invent numbers

Numbers make impact legible: latency, revenue, users, %, time saved, team size, scale (QPS, rows, $). Mine the brain dump for anything measurable and surface it.

When the impact is real but the number is missing, **do not fabricate one** — a made-up metric on a resume is a liability. Instead, either:
- ask the user for the specific figure, or
- write the bullet with a clear placeholder like `[X%]` / `[$X]` so they know to fill it in.

Two limits keep this honest and readable:
- Placeholders are for missing numbers on impact the user actually described. Don't invent the impact claim itself and leave the number blank — *"Reduced triage time by [X%]"* is fabrication if the user never said triage time improved.
- Cap it at 2-3 placeholders total, on the bullets where a number matters most; a resume full of `[X]`s reads like a form. For the rest, write the strongest honest bullet without a number.

## Honesty beyond the numbers

Fabrication isn't only made-up metrics. Three subtler failure modes, all of which surface constantly in real brain dumps:

- **Unrealized outcomes.** A prototype, proposal, or POC that never shipped did not *achieve* its intended outcome — it *targeted* or *demonstrated* it. "Built a prototype that reduced downtime" is a false claim if the prototype was never deployed; write "targeting downtime reduction" or "projected to reduce downtime." The award, the pilot, the leadership buy-in are the real, claimable results.
- **Ambiguous metrics.** "Raised attendance ~80%" could mean raised *by* 80% or raised *to* 80% — wildly different claims. When a number's meaning is ambiguous in the source material, flag it in the notes for the user to resolve rather than silently picking one.
- **Inferred impact.** If the user described building a dashboard but never said forecasts got more accurate, "improving forecast accuracy" is your inference, not their claim. Either ask, or flag it in the notes as unverified.

## Write for the skimming stranger

- Bullets are read by recruiters, HR screeners, and often non-native speakers — not domain insiders. 
- Prefer words any of them understands: "unplanned absences" over "ad hoc leave." Expand acronyms on first use — *Not as Advertised (NASD)* — unless they're universally known (API, SQL). 
- Internal team names, codenames, and company jargon mean nothing outside the company; translate them.

## Read between the lines

Brain dumps bury the good stuff in casual phrasing. "I ended up owning the migration because no one else would" is *initiative and ownership* — surface it. "Helped the new hires get ramped up" is *mentorship*. Pull the latent accomplishment out; don't just transcribe.

## Role emphasis

**Software Engineer** — technical depth is the point. Name the hard problem, the scale, and the measurable result. Concrete tech and systems belong here.

**Program / Product Manager** — show enough technical depth to be credible, but lead with planning, design, cross-team coordination, and initiative. Keep big-company work (Google, Microsoft, Apple) light on implementation detail. Actively look for and elevate:
- **Self-driven projects** — a side project, tool, or community they built and ran themselves; proof they can drive something end-to-end without being told to.
- **Organizing large events** — leadership and logistics at scale.
- **Teaching, mentoring, or training roles** — communication and leadership.

These often live outside the "job" section of a brain dump; don't let them get lost.

**Any other role** (operations, marketing, analyst, QA, support…) — follow the PM emphasis: lead with outcomes, ownership, and initiative rather than implementation detail, and quantify scale wherever the material allows.

## Output

Return **only** a bullet list — no resume layout, summary, or headers beyond light grouping.

- Group bullets under the role, company, or project they belong to.
- If a strong item doesn't fit a job (side project, teaching, event), give it its own small group.
- Where you inserted a `[X]` placeholder, flagged an ambiguous or unverified claim, or made a judgment call, note it briefly at the end so the user can verify.
- In review mode, note *why* each changed bullet was changed (which rule it violated) so the user learns the pattern.
