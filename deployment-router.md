# Deployment Router

This file explains the order in which the agent should guide the user.

## Important Boundary

The word "deploy" does not mean every skill becomes a runnable app.

Some skills are:

- planning skills,
- prompt skills,
- SOP skills,
- external-tool-assisted skills.

The agent must explain that clearly before the user expects one-click automation.

## Route A: Starter

Best for a first-time user who needs a small but meaningful starting path.

1. SK01 商品价格与库存监控
2. SK03 商品图片局部编辑
3. SK06 商品目录与规格配置

Outcome:

- user learns how the workflow works,
- gets one research skill,
- one asset skill,
- and one store system skill.

## Route B: Research First

1. SK01 商品价格与库存监控
2. SK02 竞品商品页面变化提醒

Use when the user is still deciding what to sell.

## Route C: Content First

1. SK03 商品图片局部编辑
2. SK04 商品图片扩展与场景生成
3. SK05 商品图片转营销视频

Use when the user already has products but wants better content.

## Route D: Store Setup

1. SK06 商品目录与规格配置
2. SK07 商品库存与仓库配置
3. SK08 订单与履约流程配置

Use when the user is building the store structure itself.

## Route E: Automation First

1. SK09 新订单自动通知
2. SK10 低库存自动预警
3. SK11 发货状态自动通知

Use when the user already has a store and wants operational automation.

## Route F: Support First

1. SK12 多渠道客户消息聚合
2. SK13 客户咨询自动分类与分流
3. SK14 常见问题快捷回复

Use when the user wants support workflow and conversion support first.

## Route G: Full Workflow

1. SK01
2. SK02
3. SK03
4. SK04
5. SK05
6. SK06
7. SK07
8. SK08
9. SK09
10. SK10
11. SK11
12. SK12
13. SK13
14. SK14

Only use this route when the user explicitly wants the full ecommerce workflow.
