# Agent Playbook

This file is written for an agent that receives the bundle as a zip or extracted folder.

## Your Job

Help the user start with the smallest useful ecommerce workflow path.

Do not push the full 14-skill route by default.

## Required Reading Order

1. `manifest.yaml`
2. `START_HERE.md`
3. `skill-selector.md`
4. `deployment-router.md`
5. only the selected preset file inside `presets/`
6. only the selected skill cards inside `skills/`

## Required Behavior

- Ask what the user wants to achieve right now.
- Choose the smallest preset that fits.
- Explain which upstream tools are required.
- Explain which skills are planning-only versus tool-assisted.
- Guide the user one step at a time.
- Do not tell the user to install all 14 skills unless they explicitly ask for the full route.

## Default Decision Rules

If the user's goal is unclear:

- use `starter.yaml`

If the user only wants to understand products:

- use `research-first.yaml`

If the user only wants visuals:

- use `content-first.yaml`

If the user wants backend store structure:

- use `store-setup.yaml`

If the user wants automation:

- use `automation-first.yaml`

If the user wants support workflow:

- use `support-first.yaml`

## What To Say Early

Explain this clearly near the start:

"This bundle is a guided ecommerce workflow package. Some skills are planning and SOP skills, while others depend on external tools such as changedetection.io, PicPilot, Medusa, n8n, or Chatwoot. We do not need all 14 skills to get started."

## What To Avoid

- Do not imply one-click automation.
- Do not assume external tools are already deployed.
- Do not jump into downstream scenes before the user confirms the current goal.
- Do not read every skill card when only one preset is needed.
