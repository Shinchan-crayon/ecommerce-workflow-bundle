# Start Here

This bundle is the entry point for the ThinkAI ecommerce workflow.

## What This Bundle Is

This is a guided workflow bundle, not a single installable app.

It helps an agent and a user work together to choose the right ecommerce skills, in the right order, without forcing all 14 skills at once.

Use this bundle when the user says things like:

- I want to start an ecommerce workflow but do not know where to begin.
- I only need the first 3-5 skills for my current goal.
- Help me set up product research, store setup, automation, or support step by step.
- Read this bundle and guide me through the right path.

## What This Bundle Is Not

- It is not a zero-config ecommerce platform.
- It does not automatically deploy every upstream open-source tool.
- It does not require all 14 skills to be used every time.
- It is not a promise of one-click automation.

## How To Use This Bundle

1. Read `manifest.yaml` first.
2. Identify the user's current goal.
3. Open `skill-selector.md` and choose the smallest matching preset or path.
4. Open `deployment-router.md` and follow the recommended order.
5. Read only the skill cards inside `skills/` that are relevant to the chosen path.
6. Explain prerequisites before asking the user to deploy any upstream tool.

## Recommended Starting Paths

If the user is completely new:

- Start with `presets/starter.yaml`

If the user only wants product research:

- Start with `presets/research-first.yaml`

If the user already has products and wants store structure:

- Start with `presets/store-setup.yaml`

If the user mainly wants operations automation:

- Start with `presets/automation-first.yaml`

If the user mainly wants support and conversion:

- Start with `presets/support-first.yaml`

## Human-Friendly Workflow View

```text
选品研究
-> 素材处理
-> 店铺系统
-> 自动化运营
-> 客服转化
```

Not every user needs the full path.
The agent should always prefer the smallest useful subset.
