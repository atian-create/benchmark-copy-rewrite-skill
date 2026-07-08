# Benchmark Copy Rewrite Skill

Open Skill for extracting reusable copywriting structure from benchmark content, then rewriting it with the user's own topic, audience, proof, and truthful material.

中文一句话：把参考文案提炼成可复用结构，再填入自己的真实材料，而不是照搬别人。

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
