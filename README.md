# tim0n / Urban Renaissance

我为一个组织里同时存在人和 AI 智能体的世界，设计能够承担责任的系统。

I build systems for a world where agents can act: who intends, who commits, who is authorized to act, and who checks that it actually happened.

我的项目反复追问同一个问题：

> 当系统可以替你行动时，谁保留意图，谁承担责任，谁授予权限，谁核验结果？

```
intent → request → commitment → authorization → action → verification
意图   →  请求   →    承诺     →     授权      →  行动  →    核验
```

## Projects

### [LeuBai 留白](https://github.com/tim0n1994/leubai-v2)

**把时间还给人。**

A local-first Personal Agency Layer for keeping intent, responsibility, authorization, action, and protected time on one verifiable timeline.

请求不自动成为责任，建议不自动成为授权，执行也不自动等于外部结果已经发生。

[Preview release v0.0.0-preview.1](https://github.com/tim0n1994/leubai-v2/releases/tag/v0.0.0-preview.1) · [README](https://github.com/tim0n1994/leubai-v2/blob/main/README.md)

### [Muses](https://github.com/tim0n1994/muses)

**The local state machine between developer signals and machine action.**

Muses turns editor and session signals into explainable belief state, conservative policy, and reversible soundscape effects. It keeps the seam between inference and action visible: `signal → state → policy → effect → receipt`.

把开发者周围的真实信号变成可解释的状态、保守的策略和可回看的声音动作；未知可以保持未知，行动必须留下证据。

[Internal preview v0.3.0-internal.2](https://github.com/tim0n1994/muses/releases/tag/v0.3.0-internal.2) · [README](https://github.com/tim0n1994/muses/blob/main/README.md) · [CI](https://github.com/tim0n1994/muses/actions/runs/40081644038)

### [Udify](https://github.com/tim0n1994/udify)

**Tell a game what to change. Approve the patch before it touches your files.**

Intent-driven content evolution: Udify reads a game's structure, turns a plain-language request into atomic edits, shows the evidence, validates the result, and keeps the change reversible.

[Public technical preview v0.1.0-alpha.1](https://github.com/tim0n1994/udify/releases/tag/v0.1.0-alpha.1) · [双语 README](https://github.com/tim0n1994/udify/blob/main/README.zh-CN.md)

创作在这里是变换，不是生成。

### [Salon9](https://github.com/tim0n1994/salon9)

**AI 原生实时语音圆桌：AI 永不入场。**

事件流和隐形工作人员把对话变具体、可检索，并把发布权留给参与者。

[Private beta v0.1.0-beta.1](https://github.com/tim0n1994/salon9/releases/tag/v0.1.0-beta.1)

### [WooshaLoop](https://github.com/tim0n1994/wooshaloop)

**把情绪信号变成可回应、可回看的回路。**

An internal MVP for signals, responses, consent, and weekly loop weather, with the contract and CI gate kept explicit.

[Internal preview v0.1.0-internal.4](https://github.com/tim0n1994/wooshaloop/releases/tag/v0.1.0-internal.4)

### [Eagleye](https://github.com/tim0n1994/eagleye)

**A scraper stops at documents. Eagleye keeps the chain from source to brief inspectable.**

An evidence-linked intelligence pipeline for collection, enrichment, translation, knowledge graph work, and operator-facing briefs. Provenance, feed health, retry state, and runtime boundaries stay visible in the design.

[Internal release v1.1.0-internal.1](https://github.com/tim0n1994/eagleye/releases/tag/v1.1.0-internal.1) · [latest CI](https://github.com/tim0n1994/eagleye/actions/runs/40056951943)

### [World Patch 现实补丁](https://github.com/tim0n1994/ohmyrokid)

**让眼镜理解你想要的现实，并带你把它改出来。**

A Rokid Glasses prototype that observes the current world, compares it with a target state, guides a step-by-step patch, and verifies each transition.

### [Neosoul](https://github.com/tim0n1994/Neosoul)

**Voice social without the paywall maze.**

A public Next.js/PWA voice-social prototype with visible safety boundaries and Supabase/LiveKit seams. v0.1.1 is deployed on Vercel; CI, provider smoke, and public auth E2E are green. Stripe remains optional future work, while moderation and payouts remain open.

[Public stable release v0.1.1](https://github.com/tim0n1994/Neosoul/releases/tag/v0.1.1) · [README](https://github.com/tim0n1994/Neosoul/blob/main/README.md) · [CI](https://github.com/tim0n1994/Neosoul/actions/runs/40204840121)

### [Ether — Eclipse](https://github.com/tim0n1994/Ether)

**Remix in the space between recognition and surprise.**

A private Vite/React UI prototype for original↔novelty balance, stem controls, and a context-agent surface using simulated track data. Production audio inference and hardware integration remain unverified.

[Private preview v0.0.0-preview.1](https://github.com/tim0n1994/Ether/releases/tag/v0.0.0-preview.1) · [README](https://github.com/tim0n1994/Ether/blob/main/README.md) · [CI](https://github.com/tim0n1994/Ether/actions/runs/40119251441)

### [FiatCine — Digital Backlot](https://github.com/tim0n1994/FiatCine)

**Turn a script into a shot plan, then move from assets to director decisions.**

A private AI filmmaking and previsualization prototype: Script → Shot List → Asset Gym → Director Console. Typecheck and build pass; rendering, export, and a complete production asset pipeline remain planned.

[Private preview v0.0.0-preview.1](https://github.com/tim0n1994/FiatCine/releases/tag/v0.0.0-preview.1) · [README](https://github.com/tim0n1994/FiatCine/blob/main/README.md) · [CI](https://github.com/tim0n1994/FiatCine/actions/runs/40119593325)

### [Genesis OS](https://github.com/tim0n1994/Genesis)

**Make an organization's DNA, authority, health, and growth visible.**

A private organization-modeling prototype with a Vite/React surface for setup, roles, health, settlement, immersion, and growth. Authentication, durable data, and real-time collaboration remain open.

[Private preview v0.0.0-preview.1](https://github.com/tim0n1994/Genesis/releases/tag/v0.0.0-preview.1) · [README](https://github.com/tim0n1994/Genesis/blob/main/README.md) · [CI](https://github.com/tim0n1994/Genesis/actions/runs/40119729521)

### [Genesis Org OS](https://github.com/tim0n1994/genesis-org)

**From Foundation to Operation, Growth, and Incentive.**

A private frontend/backend organization OS prototype. Both build surfaces pass; authentication, database persistence, WebSockets, billing, and production operations remain open.

[Private preview v2.1.0-preview.1](https://github.com/tim0n1994/genesis-org/releases/tag/v2.1.0-preview.1) · [README](https://github.com/tim0n1994/genesis-org/blob/master/README.md) · [CI](https://github.com/tim0n1994/genesis-org/actions/runs/40119865754)

### [atman](https://github.com/tim0n1994/atman)

**Contributing to a flow-driven agent runtime.**

我在这个 fork 中补充 fmt、clippy 和 test CI；项目本体属于 [W-Mai/atman](https://github.com/W-Mai/atman)。

### [REA](https://github.com/tim0n1994/rea)

**Reverse Engineer Anything.**

A fork of [morluto/rea](https://github.com/morluto/rea): one MCP surface for understanding binaries, applications, and runtime behavior.

### [DeepInfer](https://github.com/tim0n1994/DeepInfer)

**High-performance inference, kept close to the upstream implementation.**

A fork of [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer), maintained as a downstream workspace with upstream attribution intact.

### [NanoSparks](https://github.com/tim0n1994/nanosparks)

**把真实对话变成带时间证据的思维单元、洞察图谱和可复用上下文。**

NanoSparks is the human thought infrastructure line: source material becomes timestamped evidence, structured thought, and context that can be searched and reused.

[Internal preview v0.1.0-internal.1](https://github.com/tim0n1994/nanosparks/releases/tag/v0.1.0-internal.1)

### [Apollo](https://github.com/tim0n1994/Apollo)

**Air Instrument V3：把空气做成一种可演奏、可感知的接口。**

An openvela based bimanual AI air instrument prototype for the 2026 openvela AI Hardware Contest.

[Pre-release firmware v0.1.0-demo.3](https://github.com/tim0n1994/Apollo/releases/tag/v0.1.0-demo.3)

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