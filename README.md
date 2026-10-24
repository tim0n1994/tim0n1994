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

**An intelligence pipeline hosted on Argus ThinkPad.**

The internal release packages the verified code line; live corpus, credentials, and ThinkPad runtime remain deployment inputs.

[Internal release v1.1.0-internal.1](https://github.com/tim0n1994/eagleye/releases/tag/v1.1.0-internal.1)

### [World Patch 现实补丁](https://github.com/tim0n1994/ohmyrokid)

**让眼镜理解你想要的现实，并带你把它改出来。**

A Rokid Glasses prototype that observes the current world, compares it with a target state, guides a step-by-step patch, and verifies each transition.

### [atman](https://github.com/tim0n1994/atman)

**Contributing to a flow-driven agent runtime.**

我在这个 fork 中补充 fmt、clippy 和 test CI；项目本体属于 [W-Mai/atman](https://github.com/W-Mai/atman)。

### [REA](https://github.com/tim0n1994/rea)

**Reverse Engineer Anything.**

A fork of [morluto/rea](https://github.com/morluto/rea): one MCP surface for understanding binaries, applications, and runtime behavior.

### [DeepInfer](https://github.com/tim0n1994/DeepInfer)

**High-performance inference, kept close to the upstream implementation.**

A fork of [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer), maintained as a downstream workspace with upstream attribution intact.

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