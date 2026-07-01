# OPC Company Deploy Blueprint

A deployment blueprint for turning AI chat setups into a **repeatable one-person-company operating system**.

This skill packages a practical operating model for solo founders, independent developers, and small AI teams who want more than chatbot tricks — they want a real system for tasks, collaboration, content production, product ops, QA, and delivery.

## Why this project exists

Most AI workflows stop at “ask a model, get an answer.”  
That is not a company.

This project captures a different pattern:

- org chart instead of ad-hoc prompts
- task lifecycle instead of chat memory
- shared workspace instead of scattered notes
- delivery rules instead of vague progress
- QA gate instead of hopeful publishing
- content/product SOPs instead of random output

The goal is to help founders move from **AI user** to **AI operator**.

## What this skill provides

### 1. A repeatable operating model

The blueprint defines a simple company structure:

- **Chairman** — direction, approvals, authorization boundary
- **CEO / Orchestrator** — decompose tasks, route work, enforce delivery
- **dev** — MVP, automation, scripts, technical delivery
- **research** — market, competitors, trends, intelligence
- **finance** — cashflow, ROI, budget, risk alerts
- **ops** — channels, publishing, SOPs, customer ops
- **qa** — fact check, compliance, quality gate

### 2. A clear task lifecycle

Universal tasks:

```text
Inbox -> Assigned -> In Progress -> Review -> Done | Failed
```

Software R&D tasks:

```text
待开始 -> 需求评审 -> UI评审 -> 技术方案评审 -> 开发编码 -> 功能测试 -> 回归测试 -> 验收上线 -> 已完成
```

Non-R&D tasks:

```text
待开始 -> 进行中 -> 已完成
```

### 3. Delivery and QA discipline

This skill assumes:

1. Every non-trivial task should pass QA.
2. Every deliverable should land in a shared workspace.
3. Every status change should leave a progress note.
4. Public publishing requires explicit approval.

## Who this is for

This blueprint is useful if you are building:

- a one-person AI company
- a solo founder operating system
- an internal AI ops framework
- a client-facing “AI company setup” service
- a Hermes / Feishu / task-board based delivery workflow

## Repository structure

```text
SKILL.md
references/
  deploy-sop.md
  launch-checklist.md
  service-offers.md
scripts/
  README.md
templates/
  client-kickoff.md
```

### Recommended workspace structure

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

## How to use

### Use as a deployment guide

Use `SKILL.md` as the main operating manual:

- org model
- task lifecycle
- delivery rules
- workspace layout
- Feishu collaboration layer
- content SOP
- service packaging

### Use for client projects

Use this repo when you need to help a client set up:

- AI org structure
- task routing
- delivery workflow
- shared documentation
- review gates
- publishing SOP

### Use as a service blueprint

This repo is also intended to support service packaging:

1. OPC deployment service
2. monthly operating partner
3. template pack
4. AI content factory setup
5. task automation setup

See `references/service-offers.md`.

## Recommended collaboration fields

If you connect this model to Feishu or another task board, use these fields:

- 任务ID
- 标题
- 状态
- 负责人
- 优先级
- 产物路径
- 飞书文档
- QA审查

## Content factory SOP

A simple content operations chain:

```text
热点收集 -> 选题池 -> 脚本/图文 -> 封面 -> 视频草稿 -> QA审查 -> 发布包 -> 授权发布 -> 多平台分发 -> 数据复盘
```

## Model tiering recommendation

Not every task should use the same model.

| tier | example use | example |
|---|---|---|
| strong reasoning | CEO, delegation, planning, curation | high-capability model |
| multimodal / vision | image understanding, UI inspection | multimodal model |
| lightweight | summaries, extraction, drafts | cheaper/faster model |

This repo intentionally avoids hardcoding provider-specific promises.  
The important part is **tiering**, not one specific vendor choice.

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

See `references/launch-checklist.md`.

## What this skill is NOT

This is **not** a magic automation that makes money by itself.  
This is **not** a prompt collection.  
This is **not** a guaranteed growth hack.

It is an **operating blueprint**.

The value comes from consistent execution, not from AI alone.

## Suggested naming

You can position this as:

- AI company operating system
- one-person-company deployment blueprint
- solo founder AI ops framework
- AI task and delivery system setup
- AI operations service packaging

## Contributing

Contributions are welcome, especially:

- better SOP wording
- more practical templates
- real-world deployment examples
- improved service packaging language
- clearer onboarding docs

If you add a new workflow, please keep it practical and implementation-oriented.

## License

MIT

## Credits

This repo is based on a real operating pattern used to run an OPC-style AI business, then packaged into a reusable blueprint for deployment and service delivery.
