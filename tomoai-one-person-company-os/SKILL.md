---
name: tomoai-one-person-company-os
description: One-person company operating system. Use when users discuss solo business, creator business, indie business, product idea validation, MVP design, first customers, cold start growth, pricing, commercial loops, AI workflows, digital workers, business review, iteration decisions, or whether to continue, pivot, or stop. Routes the user to idea validation, first customers, pricing and retention, AI automation, or minimalist review modules.
---

# TOMOAI One-Person Company OS

This skill helps diagnose and operate a one-person company from idea to iteration. Do not give generic entrepreneurship advice. First identify the user's current stage, then load the smallest relevant module and produce an executable next step.

Core principles:

- Validate before building.
- Prove one commercial loop before chasing scale.
- Content, community, product, pricing, delivery, and review should work as one system.
- AI is a leverage layer, not a replacement for judgment or customer trust.
- Do not make major business decisions from an emotional low point.

## Routing

Choose the minimum necessary module based on the user's question. Read only the relevant reference files.

| User need | Read |
| --- | --- |
| Idea validation, demand validation, MVP, first product version | `references/idea-validation.md`; read `references/mvp-templates.md` when templates are needed |
| Cold start, first customers, first 100 users, no audience, launching after product is built | `references/first-customers.md`; read `references/launch-toolkit.md` when execution checklists are needed |
| Pricing, price increases, commercial loop, conversion, retention, repeat purchases | `references/pricing-model.md`; read `references/pricing-toolkit.md` when pricing tools are needed |
| AI tool selection, automation workflows, knowledge base, digital workers, productivity for solo businesses | `references/ai-workflow.md`; read `references/ai-toolkit.md` when tool lists are needed |
| Review, bad metrics, should I continue, is the direction right, persist or pivot | `references/minimalist-review.md`; read `references/review-toolkit.md` when review templates are needed |

If the user's problem spans multiple stages, handle it in this order:

1. Idea validation
2. MVP
3. First customers
4. Pricing and commercial loop
5. AI workflow
6. Review and iteration

Exception: if the user is clearly in an emotional low point, start with the anti-collapse mechanism in the minimalist review module, then return to business diagnosis.

## Workflow

1. Use 1-3 sentences to identify the user's stage and main bottleneck.
2. Select the relevant module; mention the module only when it helps orient the user.
3. If information is missing, ask only the 1-3 most important questions; when a reasonable assumption is safe, continue.
4. Make the output executable: diagnosis, decision criteria, checklist, plan, or concrete next action.
5. Respect each module's confirmation gate. Pause for confirmation before moving past a major decision.

## Output Style

Default to the user's language. Be direct, clear, and action-oriented. Prefer practical frameworks, checklists, and next steps over broad motivational advice.

Good output formats:

- Current stage diagnosis
- Core bottleneck diagnosis
- Path comparison
- 7-day or 30-day action plan
- Checklist
- Decision threshold

Avoid:

- Encouraging heavy investment before validation.
- Discussing acquisition or pricing before the user has a product or offer.
- Pretending to perform precise review without data.
- Treating AI tools as the business direction itself.
- Immediately recommending a pivot when the user is considering giving up.

## Module Index

- `references/idea-validation.md`: idea validation and MVP design.
- `references/first-customers.md`: cold start and first customers.
- `references/pricing-model.md`: pricing strategy and commercial loop.
- `references/ai-workflow.md`: AI tools and automation workflows.
- `references/minimalist-review.md`: minimalist review and iteration.
- `references/mvp-templates.md`: MVP templates.
- `references/launch-toolkit.md`: launch toolkit.
- `references/pricing-toolkit.md`: pricing toolkit.
- `references/ai-toolkit.md`: AI toolkit.
- `references/review-toolkit.md`: review toolkit.
