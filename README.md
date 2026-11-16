# Partner Enablement Skill

An open, opinionated workflow for creating technical partner training that another instructor can deliver consistently. It covers sales, implementation, integration, and support through one skill.

**The AI owns instructional alignment. People review suitability and deliverability.** The course owner should not need to be an instructional design expert to identify a poorly designed course.

## Status

Early development, version 0.1. The design standard and webhook example blueprint have passed stage-specific multiagent reviews. There is no completed course, executable lab, validated certification, instructor trial, or learner pilot yet. The skill has structural validation, not a completed end-to-end behavioral evaluation. Agent consensus is not proof of effectiveness.

## Workflow

1. Establish audience, prerequisites, tasks, sources, objectives, and evidence of success.
2. Draft a blueprint and audit its concrete design commitments.
3. Author the course in Markdown with explanations, worked examples, progressively less guided practice, diagnostic feedback, retrieval, transfer, and assessments.
4. Independently review instructional design, assessment, instructor handoff, technical integrity, and consistency. Revise and recheck findings before human review.
5. Produce a Word review copy. People check partner fit, practical use, and whether someone other than the author could deliver it.
6. Reconcile changes into Markdown, repeat affected checks, and generate final formats after approval.
7. Verify actual technical execution, rendered outputs, instructor handoff and learner pilot evidence before claiming delivery readiness.

A blueprint pass is not a manuscript pass. A sound plan does not establish that its eventual lessons, labs or questions are good.

## Contents

| Path | Purpose |
| --- | --- |
| [SKILL.md](skills/partner-enablement/SKILL.md) | Compact agent workflow and stage gates |
| [Design standard](skills/partner-enablement/references/design-standard.md) | Binding instructional rules, defaults, review process and source basis |
| [Review protocol](skills/partner-enablement/references/review-protocol.md) | Independent reviewer prompts and finding format |

## Use

For assistants supporting directory-based skills, place `skills/partner-enablement` in the product's supported skill location and follow its installation instructions. Paths and discovery differ by product; this repository does not install itself.

For other assistants, supply `SKILL.md` and both reference files as project instructions. Do not assume that a product supports independent subagents: the skill requires disclosed sequential review passes when separate agents are unavailable.

Example request:

> Use the partner enablement skill to design a foundation for our integration partners. Start with the blueprint. Audit instructional alignment before producing the Word suitability review copy. Use the supplied product documentation for product claims and label unverified implementation assumptions.

## Deliverables

Markdown is canonical; Word is the review format. Final live-training packages normally include a student DOCX workbook, standalone participant reference PDF, instructor PPTX with substantive speaker notes, and separate instructor DOCX guide with solutions and scoring guidance. Each serves its own purpose.

Certification is optional. Documentation and approved AI assistance are permitted by default. Certification claims must describe what was actually assessed; quizzes do not replace practical evidence.

## Source basis

The workflow draws on [The Carpentries](https://carpentries.github.io/instructor-training/), [Diataxis](https://diataxis.fr/), [Google Technical Writing](https://developers.google.com/tech-writing), [How People Learn II](https://doi.org/10.17226/24783), [Applying Science of Learning in Education](https://teachpsych.org/ebooks/asle2014/), and [Cathy Moore's action mapping resources](https://blog.cathy-moore.com/book-resources/).

These sources have different scopes. Research informs teaching requirements; documentation frameworks govern document purpose and clarity. Exact timing, passing scores, artifact formats and the review council are project policies, not research-proven universal constants. See the design standard for the mapping.

Third-party books, website archives and PDF collections are not included. Their licenses remain their own. No affiliation or endorsement is implied. Course examples and generated training materials are maintained separately from this repository.

## Contributing

Open an issue or pull request with the concrete problem, affected criterion, proposed change, and small example. Prefer observable learning improvements over more process. Preserve truthful validation status and stage boundaries. Do not submit credentials, customer data, proprietary material or content you cannot redistribute.

## License

Original repository content is available under the [MIT License](LICENSE). Linked third-party materials are not covered by that license.
