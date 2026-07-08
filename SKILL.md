---
name: benchmark-copy-rewrite
description: "Open Skill for extracting reusable copywriting structure from benchmark content, then rewriting it with the user's own topic, audience, proof, and truthful material. Use when the user asks for benchmark copy rewrite, Xiaohongshu copywriting template, RedNote caption rewrite, content imitation without copying, 对标文案改写, 小红书文案模板, 文案仿写, 套框架. This Skill uses user-provided material and public-safe reasoning only; it does not publish automatically, scrape private data, copy creators, or promise growth."
---

# Benchmark Copy Rewrite

## Purpose

把参考文案提炼成可复用结构，再填入自己的真实材料，而不是照搬别人。

This is a lightweight standalone open Skill. It turns a repeated creator task
into a clear Agent workflow with inputs, checks, output shape, and boundaries.

## Use This For

- template skeleton
- style parameters
- slot table
- non-copyable list
- 1-3 adapted drafts
- originality self-check

## Do Not Use This For

- automatic publishing
- private account login
- private data extraction
- guaranteed traffic, growth, sales, or viral outcomes
- copying another creator's exact wording, identity, images, or claims
- making claims that the user's material does not support

## Inputs

- 1-3 benchmark captions, scripts, screenshots, or templates
- user topic, product, audience, city, case, or personal story
- desired platform and format
- tone target: practical, friendly, sharp, emotional, or instructional
- must-keep facts and claims to avoid

If the input is incomplete, proceed with a first-pass version and mark
assumptions. Ask only the smallest necessary follow-up when the missing detail
would materially change the result.

## Workflow

Read `references/workflow-rules.md` when the task needs the full rule set.

- Extract the structure before writing.
- Extract style without copying exact sentences.
- Build slots for audience, pain, scene, proof, method, result, and next action.
- Mark non-copyable elements.
- Fill only truthful user material into the slots.
- Run a final originality and claim check.

## Output Contract

```markdown
## 1. Scope And Assumptions

## 2. Input Reading

## 3. Main Judgment

## 4. Working Table Or Checklist

## 5. Recommended Next Action

## 6. Boundaries
```

## Quality Bar

- Be specific and operational.
- Prefer a small usable output over a broad lecture.
- Explain why each recommendation fits the user's material.
- Mark weak evidence instead of pretending certainty.
- Do not promise results.
- Do not copy another creator's protected expression or personal story.

## Tone

Write in the user's language. For Chinese creator tasks, default to clear,
practical Chinese.

## Public Boundary

Keep examples generic. Do not include internal thread IDs, private file paths,
unpublished customer material, private account data, or internal product notes.
