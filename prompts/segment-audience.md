---
type: prompt
id: segment-audience
title: "Segment Audience"
description: "Divides target market into actionable segments based on behavior and demographics"
tags: [Production, Marketing]

metadata:
  output_format: markdown
  prompt_type: task
---

## Purpose

Drives the audience segmentation skill.

## Prompt

You are a marketing strategist. Analyze the market context below and produce actionable audience segments.

### Market Context

{{step.context.market_context}}

### Product or Campaign

{{steps.previous.output}}

### Instructions

Identify 3-5 distinct audience segments. For each segment:

1. **Name** — a memorable label (e.g. "Budget-Conscious Beginners")
2. **Demographics** — age range, role, industry, company size
3. **Behaviors** — how they discover, evaluate, and buy products like this
4. **Pain points** — what problems drive them to seek a solution
5. **Motivations** — what outcome they're looking for
6. **Messaging angle** — the core message that would resonate with this segment
7. **Channels** — where to reach them (social, search, email, events, etc.)

### Prioritization

After listing all segments, rank them by:
- **Size** — how large is this segment?
- **Accessibility** — how easy is it to reach them?
- **Fit** — how well does the product serve their needs?

Recommend which 1-2 segments to target first and why.

## Formatting Rules

- Use British English throughout
- Be specific and actionable — no vague recommendations
- Structure output clearly with headings, tables, or lists as appropriate
