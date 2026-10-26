---
name: resume-rac-editor
description: Edit resumes into evidence-backed Result-Action-Context bullets with balanced single-line length, meaningful phrase bolding, and visually verified one-page PDF layout. Use when drafting or refining resume bullets and their presentation.
---

# Resume RAC Editor

Create selective, defensible resume edits that communicate impact at a glance. Default to a one-page resume, complete single-line bullets, and consistent visual line length unless the user specifies another format. Preserve the existing template and typography.

## Establish scope and evidence

- Read the current editable resume and the supplied transcript, project artifacts, or relevant career notes before proposing additions. Resolve the exact target document and active tab/file; do not hard-code a previous resume link.
- Use the target role to select the strongest relevant evidence. Do not add every activity merely because it is recent.
- Treat each metric as a claim: establish value, unit, period, population, attribution, and whether it is measured or estimated. Explicit user confirmation can resolve a conflicting draft metric; do not describe it as independently verified.
- Distinguish delivery, usage, matches, completed collaborations, and business outcomes. A project match is not a completed collaboration; a PoC is not a scaled production launch. Team patent totals are not automatically personal patent totals.
- If sources conflict, ask only for the missing facts that affect the claim and continue independent editing. Do not choose a convenient figure, manufacture percentages, or add unsupported causality.
- Keep unresolved verification notes in a separate review artifact. Do not remove the caveat while retaining an unconfirmed result as established fact. Preserve those notes and disclose any omitted claim. Reconcile repeated claims in the summary and other authorized sections.

## Write Result → Action → Context

Lead each primary bullet with the strongest defensible result, explain the candidate's action, and end with the relevant user, problem, or operating context.

Pattern: **Result and scale** + **by/through action** + **for/in context**.

- Prefer quantified outcomes such as time saved, conversion change, adoption, cost, or throughput when supported. Preserve the time unit: hours per month cannot become hours per week.
- When no business outcome was measured, use a concrete delivery or observed usage result. Identify it accurately; do not pad the result with a technology count.
- Preserve team ownership. Do not call delivery independent when interns, colleagues, or partners contributed.
- Keep one complete thought per bullet. Split distinct evidence into a second or third standalone bullet rather than wrapping an overloaded sentence or adding fragments. Combine overlapping context where it makes a stronger coherent bullet.
- Supporting bullets may describe a specific action when no separate result exists. Do not invent a numeric result simply to force RAC onto every supporting line.
- Use consistent punctuation, clear verbs, and readable terminology. Avoid duty lists, redundant clauses, vague claims, and filler added solely to reach the right margin.
- Omit sentence-ending periods throughout the complete resume, including bullets, summaries, education descriptions and project descriptions, unless a period is critically needed for clarity or correctness. Prefer separate complete bullets or lines over multiple sentences separated by periods. Preserve necessary dots in decimal values (such as 8.52/10), email addresses, URLs, version numbers, technical names and essential abbreviations; never globally delete every `.` character.

Fictional illustrations only; never transplant these numbers into another resume:

- **Saved 12 reporting hours monthly** by automating weekly sales-report preparation for a regional operations team
- **Generated 60 project matches** for **200 pilot users** by leading a recommendation proof of concept across three student clubs
- **Delivered a recommendation proof of concept** by **leading four interns** on requirements, architecture and matching logic

## Fill the line with useful content

Use a successful single-line bullet from the user's template as the visual reference. Match its approximate rendered width, not its word or character count.

- Aim to finish near the reference's right edge with a small natural margin. Similar widths matter more than identical lengths. Do not force exact edge alignment.
- Expand short bullets using supported methods, ownership, audience, problem, scale, cadence, or technical context. Reduce long bullets by removing duplication and replacing verbose phrases.
- Keep text within the actual content column, excluding date/location columns. Measure each section against its own available width.
- Character counts are drafting aids only: font, bolding, punctuation, and glyph widths determine wrapping. A line that fits before bolding can wrap after bolding.
- Do not use justification, stretched spacing, manual spaces, font shrinking, or wider margins to simulate a filled line. Preserve font size and readability; get the wording right.
- If essential evidence cannot fit in one line, create additional complete bullets where space permits. If the one-page constraint still conflicts with required content, explain the concrete tradeoff instead of silently dropping evidence.

## Bold meaning, not isolated numbers

Select complete phrases that communicate results, scale, leadership, technical competence, discovery, or another role-relevant capability. Someone reading only the bold phrases should understand why the experience matters.

- Examples: **Saved 12 reporting hours monthly**, **Generated 60 project matches**, **leading four interns**, **field feedback, guardrails and evaluations**.
- Avoid bolding only `12`, `200`, a generic action verb, or a long sentence. Use a small number of distinct emphasis spans and keep most prose regular.
- Re-evaluate highlights after rewrites. Text replacement may inherit stale bolding; reset only the edited bullet's emphasis and apply intended spans from fresh live ranges.
- Preserve links, headings, font family/size, italics, and unrelated formatting. Do not introduce unrelated highlighting or colors.

## Edit and verify the actual artifact

Use the format's available editor/API and appropriate document skill when applicable. For Google Docs, follow the Google Docs skill's trusted read, native-preservation, revision-control, write, and export workflow; do not rebuild the document for targeted edits. For Word or LaTeX, use the relevant document workflow and native source.

1. Read live content, structure, styles, and target ranges. Record only the edit scope and relevant preservation anchors.
2. Apply selective changes using the latest revision guard where supported. Preserve table cells, tabs, dates, links, and existing layout.
3. Read back the text after index-changing edits; resolve fresh ranges before bolding. Verify the exact text and intended emphasis in the intended location.
4. Export the final native artifact to PDF after all text and formatting edits. Confirm page count, rasterize every page, and visually inspect all pages.
5. Check single-line completion, balanced width against the reference, meaningful bolding, intact content, clipping, overlaps, orphaned headings, and trailing-page spillover. Scan all resume sections for unnecessary sentence-ending periods and remove them while preserving necessary dots inside factual values, addresses and technical identifiers.
6. PDF text extraction with layout/bounding boxes can help measure line endpoints and identify wrapped lines; it supplements visual inspection. Do not use thumbnails or character counts as visual proof.
7. If excess fixed table-row height leaves blank space or causes a trailing page, adjust only that affected row to fit its content. Do not redesign the template or reduce typography to make it fit.
8. Repair observed defects locally, re-read changed areas, re-export, and inspect the revised PDF. Verify that the final version has one page when that is the agreed requirement.

For local PDF checks, discover available tools before installing anything. Poppler tools such as `pdfinfo`, `pdftotext -bbox-layout`, and `pdftoppm` support page counts, line geometry, and rasterization. Prefer bundled workspace dependencies when needed. Follow tool file-reference handling for exports and keep staging private unless the user requests an exported deliverable.

## Completion

Return the edited resume link/file and a concise account of changes. State exactly what was verified: document readback, bolding, single-line fit, visual PDF inspection, and page count. Disclose unresolved claims or unavailable rendering checks. Never claim visual verification merely because export succeeded. Do not distribute the resume or message others without authorization.
