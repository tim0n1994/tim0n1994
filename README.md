# tim0n / Urban Renaissance

我为一个组织里同时存在人和 AI 智能体的世界，设计能够承担责任的系统。

I build systems for a world where agents can act: who intends, who commits, who is authorized to act, and who checks that it actually happened.

我的项目反复追问同一个问题：

> 当系统可以替你行动时，谁保留意图，谁承担责任，谁授予权限，谁核验结果？

```
intent → request → commitment → authorization → action → verification
意图   →  请求   →    承诺     →     授权      →  行动  →    核验
```

## Public projects

These projects have public source, public release surfaces, and public evidence. Preview labels stay explicit.

### [Eagleye](https://github.com/tim0n1994/eagleye)

**A scraper stops at documents. Eagleye keeps the chain from source to brief inspectable.**

An evidence-linked intelligence pipeline for collection, enrichment, translation, knowledge graph work, and operator-facing briefs. Provenance, feed health, retry state, and runtime boundaries stay visible in the design.

[Public stable release v1.1.3](https://github.com/tim0n1994/eagleye/releases/tag/v1.1.3) · [English README](https://github.com/tim0n1994/eagleye/blob/main/README.md) · [中文 README](https://github.com/tim0n1994/eagleye/blob/main/README.zh-CN.md) · [CI](https://github.com/tim0n1994/eagleye/actions/workflows/ci.yml)

### [Neosoul](https://github.com/tim0n1994/Neosoul)

**Voice social without the paywall maze.**

A public Next.js/PWA voice-social preview with visible safety boundaries and Supabase/LiveKit seams. v0.1.3 is the current public release line; the application path has prior provider smoke and public auth E2E evidence. Stripe remains optional future work, while moderation and payouts remain open.

[Public stable preview v0.1.3](https://github.com/tim0n1994/Neosoul/releases/tag/v0.1.3) · [English README](https://github.com/tim0n1994/Neosoul/blob/main/README.en.md) · [中文 README](https://github.com/tim0n1994/Neosoul/blob/main/README.md) · [MIT License](https://github.com/tim0n1994/Neosoul/blob/main/LICENSE) · [CI](https://github.com/tim0n1994/Neosoul/actions/workflows/ci.yml)

### [LeuBai 留白](https://github.com/tim0n1994/leubai-v2)

**把时间还给人。**

A local-first Personal Agency Layer for keeping intent, responsibility, authorization, action, and protected time on one verifiable timeline. This is a public preview, not a production product; visual, deployment, and device acceptance remain separate evidence layers.

请求不自动成为责任，建议不自动成为授权，执行也不自动等于外部结果已经发生。

[Public preview v0.0.0-preview.4](https://github.com/tim0n1994/leubai-v2/releases/tag/v0.0.0-preview.4) · [English README](https://github.com/tim0n1994/leubai-v2/blob/main/README.en.md) · [中文 README](https://github.com/tim0n1994/leubai-v2/blob/main/README.md) · [MIT License](https://github.com/tim0n1994/leubai-v2/blob/main/LICENSE)

### [NanoSparks](https://github.com/tim0n1994/nanosparks)

**把真实对话变成带时间证据的思维单元、洞察图谱和可复用上下文。**

NanoSparks is the human thought infrastructure line: source material becomes timestamped evidence, structured thought, and context that can be searched and reused.

[Public stable release v0.1.2](https://github.com/tim0n1994/nanosparks/releases/tag/v0.1.2) · [English README](https://github.com/tim0n1994/nanosparks/blob/main/README.md) · [中文 README](https://github.com/tim0n1994/nanosparks/blob/main/README.zh-CN.md)

### [Udify](https://github.com/tim0n1994/udify)

**Tell a game what to change. Approve the patch before it touches your files.**

Intent-driven content evolution: Udify reads a game's structure, turns a plain-language request into atomic edits, shows the evidence, validates the result, and keeps the change reversible.

[Public technical preview v0.1.0-alpha.1](https://github.com/tim0n1994/udify/releases/tag/v0.1.0-alpha.1) · [English README](https://github.com/tim0n1994/udify/blob/main/README.md) · [中文 README](https://github.com/tim0n1994/udify/blob/main/README.zh-CN.md)

### [World Patch 现实补丁](https://github.com/tim0n1994/ohmyrokid)

**让眼镜理解你想要的现实，并带你把它改出来。**

A Rokid Glasses prototype that observes the current world, compares it with a target state, guides a step-by-step patch, and verifies each transition. It remains a hackathon preview with separate device and deployment acceptance.

[Hackathon preview v0.1.0-preview.3](https://github.com/tim0n1994/ohmyrokid/releases/tag/v0.1.0-preview.3) · [English README](https://github.com/tim0n1994/ohmyrokid/blob/main/README.en.md) · [中文 README](https://github.com/tim0n1994/ohmyrokid/blob/main/README.md) · [MIT License](https://github.com/tim0n1994/ohmyrokid/blob/main/LICENSE)

## Active private work

These are selected internal prototypes. They are listed as context for the workbench and are not public distribution surfaces.

### Muses

**The local state machine between developer signals and machine action.**

Muses turns editor and session signals into explainable belief state, conservative policy, and reversible soundscape effects. Internal preview v0.3.0-internal.2.

### Salon9

**AI 原生实时语音圆桌：AI 永不入场。**

An internal beta for event-backed, searchable conversations where publishing remains with participants. Internal beta v0.1.0-beta.1.

### WooshaLoop

**把情绪信号变成可回应、可回看的回路。**

An internal MVP for signals, responses, consent, and weekly loop weather. Internal preview v0.1.0-internal.4.

### Ether — Eclipse

**Remix in the space between recognition and surprise.**

A private Vite/React UI prototype for original↔novelty balance, stem controls, and a context-agent surface using simulated track data. Production audio inference and hardware integration remain unverified.

### FiatCine — Digital Backlot

**Turn a script into a shot plan, then move from assets to director decisions.**

A private AI filmmaking and previsualization prototype: Script → Shot List → Asset Gym → Director Console. Rendering, export, and a complete production asset pipeline remain planned.

### Genesis OS

**Make an organization's DNA, authority, health, and growth visible.**

A private organization-modeling prototype for setup, roles, health, settlement, immersion, and growth. Authentication, durable data, and real-time collaboration remain open.

### Genesis Org OS

**From Foundation to Operation, Growth, and Incentive.**

A private frontend/backend organization OS prototype. Authentication, database persistence, WebSockets, billing, and production operations remain open.

### Apollo

**Air Instrument V3：把空气做成一种可演奏、可感知的接口。**

An openvela based bimanual AI air instrument prototype for the 2026 openvela AI Hardware Contest. Pre-release firmware v0.1.0-demo.3.

## Forks with upstream attribution

These repositories remain downstream workspaces. Their upstream source, README, license, and attribution stay authoritative.

### [atman](https://github.com/tim0n1994/atman) → [W-Mai/atman](https://github.com/W-Mai/atman)

A forked flow-driven AI coding agent runtime. My downstream change is CI coverage for fmt, clippy, and tests.

### [REA](https://github.com/tim0n1994/rea) → [morluto/rea](https://github.com/morluto/rea)

A fork for reverse-engineering workflows through one MCP surface, with the upstream project remaining authoritative.

### [DeepInfer](https://github.com/tim0n1994/DeepInfer) → [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer)

A downstream workspace for the upstream high-performance DeepSeek inference framework.

### [GPU Unlock Ada](https://github.com/tim0n1994/gpu-unlock-ada) → [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada)

A public fork for downstream GPU capability work, with upstream attribution and license preserved.

## The common thread

我不把“模型说了什么”当成“世界发生了什么”。

我关心的是可追踪的状态变化：意图如何变成请求，请求何时被接受，行动由谁授权，执行留下什么证据，外部结果是否真的被核验。

## Thinking about

- Delegation and accountability when the delegate is an agent  
  当受托方是 AI，委托与问责如何重新设计
- Keeping unknowns unknown until something outside the model confirms them  
  未经外部核验的结果，就保持“未知”
- Borrowing from philosophy, biology and anthropology when a system needs a shape  
  让哲学、生物学与人类学为系统提供形状

> 求真大于一切。Truth over everything. Experiment first, and be honest about what did not work.