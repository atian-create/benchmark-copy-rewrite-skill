# 对标文案安全改写 Skill

这是一个给创作者、运营者、文案同学用的开源轻量 Skill：当你看到一篇写得很好的小红书 / RedNote 文案、口播稿、朋友圈文案或销售文案时，它不会让你照搬，而是帮你把里面真正可学习的结构提炼出来，再填入你自己的真实材料。

很多人想学习优秀文案时，会卡在两个极端：

- 完全照抄，结果像另一个人的人生、语气和经历。
- 只说“我想要类似风格”，最后改出来还是很空。

这个 Skill 做的是中间那一步：先把参考文案拆成可复用的结构、语气、节奏和槽位，再明确哪些不能复制，然后用你自己的主题、产品、案例、证明、城市、受众和真实经历重新写。

## 你下载后可以用它做什么

- 从 1-3 篇参考文案中提炼结构模板。
- 识别文案里的开头、转折、证明、情绪、结尾和行动引导。
- 把别人的表达节奏转成可填写的槽位表。
- 标出不能复制的部分：具体句子、个人经历、身份资源、虚假数字、夸大承诺。
- 用你自己的真实材料写出 1-3 版适配文案。
- 做一份“相似在哪里、原创在哪里”的自检，降低照搬风险。

## 适合谁

- 想学小红书爆文结构，但不想复制别人内容的创作者。
- 手里有参考文案，但不知道怎么变成自己版本的人。
- 做品牌内容、产品种草、朋友圈转化、口播脚本的人。
- 给客户改稿，希望把“感觉像某个风格”变成明确结构的人。
- 想让 Agent 帮自己改文案，但希望它先判断结构，而不是直接润色的人。

## 为什么这个 Skill 值得单独装

普通改写工具常见的问题是：只把句子换个说法，或者把参考文案的情绪照搬过来。

这个 Skill 会先做四个判断：

1. 参考文案真正有效的是结构、情绪、选题还是证明方式。
2. 哪些只是原作者自己的经历和身份，不能搬到你身上。
3. 你的材料是否足够支撑同样的表达强度。
4. 改完之后是不是像你自己会说的话。

它更像一个“文案结构翻译器”，把别人的可学习部分翻译成你自己的表达。

## 3 分钟上手

把这个仓库里的 `SKILL.md` 放到你的 Agent Skill 目录，然后这样问：

```text
用 benchmark-copy-rewrite 帮我处理这篇参考文案。
参考文案：[粘贴文本]
我的主题：自由职业者如何用 AI 做内容复盘
我的受众：每周更新但不知道怎么看数据的创作者
平台：小红书图文
要求：学结构，不照搬句子
```

## 你会拿到什么结果

默认输出会包括：

- 参考文案结构骨架。
- 风格参数：语气、句子长度、情绪强度、问题节奏。
- 可填写槽位：人群、痛点、场景、案例、证明、方法、结果、下一步。
- 不可复制清单。
- 1-3 版用你自己材料写出的文案。
- 原创性自检。

## 公开版边界

这个开源版不鼓励复制别人的标题、正文、经历、身份、图片或商业承诺。它只帮助你学习公开材料中的结构和表达逻辑，再写出你自己的版本。它不承诺流量、成交或爆款。

## Search Keywords

English keywords:

`benchmark copy rewrite`, `Xiaohongshu copywriting template`, `RedNote caption rewrite`, `content imitation without copying`, `copywriting framework`, `social media caption workflow`, `creator copywriting skill`, `AI skill for creators`.

中文关键词：

`对标文案改写`, `小红书文案模板`, `文案仿写`, `套框架`, `固定框架填充`, `参考文案改写`, `创作者文案工具`, `小红书正文改写`.

## Why This Exists


Creators often like the rhythm of a high-performing post but should not copy another creator's sentences, identity, story, or claims.
This Skill separates structure from source material: hook, middle route, proof, turn, ending, style parameters, and reusable slots. The final draft must be filled with the user's truthful material.

## What It Can Do

- template skeleton
- style parameters
- slot table
- non-copyable list
- 1-3 adapted drafts
- originality self-check

## Best Inputs

- 1-3 benchmark captions, scripts, screenshots, or templates
- user topic, product, audience, city, case, or personal story
- desired platform and format
- tone target: practical, friendly, sharp, emotional, or instructional
- must-keep facts and claims to avoid

## Workflow

- Extract the structure before writing.
- Extract style without copying exact sentences.
- Build slots for audience, pain, scene, proof, method, result, and next action.
- Mark non-copyable elements.
- Fill only truthful user material into the slots.
- Run a final originality and claim check.

## Output Contract

Default output:

1. Scope and assumptions
2. Input reading
3. Main judgment
4. Structured table or checklist
5. Recommended next action
6. Boundary notes

For detailed rules, see `references/workflow-rules.md`.

## Example Prompt

```text
Use $benchmark-copy-rewrite for this task:
Benchmark copy: [paste text]
My topic: how solo creators use AI to review content
Audience: creators who publish weekly but do not review results
Format: Xiaohongshu caption
```

## Example Output Shape

See `examples/sample-output.md` for a short sample.

## Open-Source Boundary

This standalone open version includes:

- reusable creator workflow instructions
- input and output contracts
- workflow rules
- example output
- Agent metadata
- MIT license

This standalone open version does not include:

- private platform credentials
- automatic publishing
- private analytics connectors
- scraping or monitoring
- guaranteed traffic, growth, sales, or viral outcomes
- copying another creator's content
- internal operating notes or private project context

## Repository Map

- `SKILL.md`: Agent entrypoint and workflow rules
- `agents/openai.yaml`: Agent display metadata
- `references/workflow-rules.md`: detailed workflow and quality rules
- `examples/sample-output.md`: sample input and output shape
- `LICENSE`: MIT license

## Recommended GitHub Description

> Open Skill for extracting reusable copywriting structure from benchmark content, then rewriting it with the user's own topic, audience, proof, and truthful material.

## Suggested GitHub Topics

`copywriting`, `benchmark-analysis`, `xiaohongshu`, `rednote`, `creator-tools`, `content-workflow`, `social-media`, `ai-skill`, `open-source`

## License

MIT
