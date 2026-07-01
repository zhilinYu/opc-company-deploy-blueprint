---
name: opc-company-deploy-blueprint
description: Deploy and replicate an OPC-style one-person-company operating system for clients. Use when the user asks to set up AI org charts, task lifecycle, Feishu collaboration, content factories, product ops, QA gates, model tiering, or to turn a chat-based AI setup into a repeatable operating business.
---

# OPC Company Deploy Blueprint

This skill packages the current OPC operating model into a repeatable deployment flow for new clients.

## When to use

Use this skill when the request is:
- build an AI company operating system
- deploy a one-person-company framework
- turn Hermes / Feishu / task boards into a business
- set up profiles, SOPs, review gates, content distribution
- productize internal AI ops into a client-ready service

## Core operating model

### Org chart

| role | responsibility |
|------|----------------|
| Chairman | direction, approvals, authorization boundary |
| CEO / Orchestrator | decompose tasks, route work, enforce delivery |
| dev | MVP, automation, scripts, technical delivery |
| research | market, competitors, trends, intelligence |
| finance | cashflow, ROI, budget, risk alerts |
| ops | channels, publishing, SOPs, customer ops |
| qa | fact check, compliance, quality gate |

### Task lifecycle

Universal tasks:
```text
Inbox -> Assigned -> In Progress -> Review -> Done | Failed
```

Software R&D:
```text
待开始 -> 需求评审 -> UI评审 -> 技术方案评审 -> 开发编码 -> 功能测试 -> 回归测试 -> 验收上线 -> 已完成
```

Non-R&D:
```text
待开始 -> 进行中 -> 已完成
```

### Delivery rules

1. Every non-trivial task must go through QA.
2. Every deliverable must land in a shared workspace.
3. Every task change should leave a progress note.
4. Publishing or public posting requires explicit client approval.

## Workspace structure

Recommended:
```text
config/
shared/specs
shared/artifacts
shared/reviews
shared/reports
templates/
scripts/
tasks/
agents/
logs/
```

## Feishu collaboration layer

Recommended fields:
- 任务ID
- 标题
- 状态
- 负责人
- 优先级
- 产物路径
- 飞书文档
- QA审查

## Model tiering

Use a three-tier model:

| tier | example use | example model |
|------|-------------|---------------|
| strong reasoning | CEO, delegation, kanban, curator | mimo-v2.5-pro |
| multimodal / vision | image understanding | mimo-v2.5 |
| lightweight | summaries, extraction, drafts | mimo-v2.5 |

## Content factory SOP

```text
热点收集 -> 选题池 -> 脚本/图文 -> 封面 -> 视频草稿 -> QA审查 -> 发布包 -> 授权发布 -> 多平台分发 -> 数据复盘
```

## Service packaging

Recommended offers:
1. OPC deployment service
2. monthly operating partner
3. template pack
4. AI content factory setup
5. task automation setup

## Deployment checklist

- [ ] workspace created
- [ ] org roles documented
- [ ] task lifecycle configured
- [ ] Feishu board linked
- [ ] webhook / bot delivery wired
- [ ] model tiering set
- [ ] content SOP created
- [ ] product SOP created
- [ ] QA gate defined
- [ ] first demo task completed

## References

- See [references/deploy-sop.md](references/deploy-sop.md)
- See [references/service-offers.md](references/service-offers.md)
- See [references/launch-checklist.md](references/launch-checklist.md)
