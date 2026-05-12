# TOMOAI One-Person Company OS

A Codex skill for diagnosing and operating a one-person company from idea validation to iteration.

This skill routes a solo business question into the right operating module:

- Idea validation and MVP design
- Cold start and first customers
- Pricing strategy and commercial loop
- AI tools and automation workflows
- Minimalist review and iteration decisions

The skill is designed for practical execution. It avoids generic startup advice and instead helps the user identify their current stage, diagnose the bottleneck, and choose the next executable step.

## Skill Folder

The installable skill is in:

```text
tomoai-one-person-company-os/
```

Core files:

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

## What It Helps With

Use it when working on:

- "Is this idea worth doing?"
- "How should I design the MVP?"
- "How do I get my first 100 users?"
- "How should I price my offer?"
- "How do I turn traffic into revenue?"
- "How can I use AI workflows in a solo business?"
- "Should I continue, pivot, or stop?"

## Design

The skill uses progressive disclosure:

- `SKILL.md` stays lean and handles routing.
- Detailed modules live in `references/`.
- The agent reads only the module needed for the current user question.

## License

MIT License.
