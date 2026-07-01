# Skill Selector

Use this file when the user does not need all 14 skills.

## Core Rule

Always choose the smallest path that can solve the user's current goal.

Do not default to the full bundle unless the user explicitly wants the full ecommerce workflow.

## Fast Matching

If the user says:

- "I am new and do not know where to start"
  Use `presets/starter.yaml`

- "I want to research products or track competitors"
  Use `presets/research-first.yaml`

- "I want better product visuals first"
  Use `presets/content-first.yaml`

- "I need to structure my store backend"
  Use `presets/store-setup.yaml`

- "I need operational automation"
  Use `presets/automation-first.yaml`

- "I need customer support and conversion setup"
  Use `presets/support-first.yaml`

- "I want the full ecommerce operating chain"
  Use `presets/full.yaml`

## Goal To Skills

| User Goal | Recommended Skills |
|---|---|
| Find products worth testing | SK01, SK02 |
| Make product visuals usable | SK03, SK04 |
| Turn product image into promo video | SK05 |
| Build product and variant structure | SK06 |
| Build inventory and warehouse rules | SK07 |
| Build order and fulfillment flow | SK08 |
| Notify team about new orders | SK09 |
| Alert low stock automatically | SK10 |
| Notify shipping status automatically | SK11 |
| Centralize customer messages | SK12 |
| Route customer inquiries | SK13 |
| Standardize FAQ replies | SK14 |

## New User Recommendation

For a first-time ecommerce user, do not start with 14 skills.

Start with these 3:

1. SK01 商品价格与库存监控
2. SK03 商品图片局部编辑
3. SK06 商品目录与规格配置

This gives the user a minimum path across research, assets, and store setup.

## Agent Behavior

- Ask what the user is trying to achieve right now.
- Pick one preset.
- Explain why that preset is smaller and easier than the full path.
- Show the user the order from `deployment-router.md`.
- Only read the matching skill cards.
