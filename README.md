# TOMOAI One-Person Company OS

An operating-system skill for solo founders, creators, indie hackers, and one-person businesses.

Most business advice is written for teams with capital, time, and specialists. This skill is for the opposite situation: one person, limited attention, too many ideas, and a real need to decide what to do next.

Use it when you want Codex to stop giving generic startup advice and start acting like a practical business operator: diagnose the current stage, choose the right module, and return a concrete next action.

## Why This Exists

One-person businesses usually fail from sequence problems, not intelligence problems.

People build before validating. They chase traffic before the offer is clear. They automate before the workflow exists. They lower prices before understanding the commercial loop. They pivot while emotionally exhausted.

TOMOAI One-Person Company OS is designed to keep the order sane:

```text
validate -> build the smallest offer -> find first customers -> price -> systemize with AI -> review and iterate
```

## What Makes It Different

- Stage-aware diagnosis instead of one-size-fits-all advice.
- Progressive modules, so the agent reads only the context needed for the current problem.
- Built-in decision gates before expensive work, pricing changes, pivots, or automation.
- Practical outputs: checklists, thresholds, 7-day plans, offer tests, launch steps, and review criteria.
- Designed for solo operators who need leverage without pretending they are a large company.

## Example Prompts

```text
Use $tomoai-one-person-company-os to check whether this product idea is worth building.
```

```text
Use $tomoai-one-person-company-os to design the smallest MVP I can sell in 7 days.
```

```text
Use $tomoai-one-person-company-os to help me find my first 20 paying customers.
```

```text
Use $tomoai-one-person-company-os to review my current business and decide whether to continue, pivot, or stop.
```

## Modules

| Situation | Module |
| --- | --- |
| "Is this idea real demand or just my imagination?" | `idea-validation.md` |
| "What is the smallest version I can test or sell?" | `mvp-templates.md` |
| "I have no audience. Where do first customers come from?" | `first-customers.md` |
| "I need a launch checklist, not vague growth advice." | `launch-toolkit.md` |
| "How should I price this offer?" | `pricing-model.md` |
| "How do I turn attention into revenue and retention?" | `pricing-toolkit.md` |
| "Where should AI actually help in this business?" | `ai-workflow.md` |
| "Which AI tools and workflows are useful for a solo operator?" | `ai-toolkit.md` |
| "Should I keep going, change direction, or stop?" | `minimalist-review.md` |
| "How do I run a lightweight business review?" | `review-toolkit.md` |

## What You Get Back

Depending on the prompt, the skill can produce:

- a current-stage diagnosis
- a bottleneck diagnosis
- a validation plan
- an MVP scope
- a first-customer plan
- a pricing recommendation
- an AI workflow map
- a continue / pivot / stop review
- a 7-day or 30-day action plan

The default output is intentionally executable. It should help you make the next move, not collect another framework.

## Install

Copy the skill folder into your Codex skills directory:

```text
tomoai-one-person-company-os/
```

The installable folder contains:

```text
tomoai-one-person-company-os/
  SKILL.md
  agents/openai.yaml
  references/
    idea-validation.md
    first-customers.md
    pricing-model.md
    ai-workflow.md
    minimalist-review.md
    mvp-templates.md
    launch-toolkit.md
    pricing-toolkit.md
    ai-toolkit.md
    review-toolkit.md
```

## Design

The skill uses progressive disclosure:

- `SKILL.md` stays lean and handles routing.
- Detailed business modules live in `references/`.
- Codex reads only the module needed for the user's current question.

This keeps the skill lightweight while still giving it enough operating depth to be useful across the full solo-business lifecycle.

## License

MIT License.
