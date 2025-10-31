# TaskFlow Product OS Demo

This is a demo Product OS for **TaskFlow**, a fictional project management platform. Use this to see how a Product OS works with realistic company context.

## What's Inside

### Context Files
- `context/product-overview.md` - What TaskFlow does and who uses it
- `context/company-strategy.md` - Q1 2025 goals and competitive landscape
- `context/user-research-ai.md` - User interviews about AI needs

### Templates
- `templates/lennys-prd-template.md` - Structure for writing PRDs

### Prompts
- `prompts/socratic-questions.md` - Framework for clarifying thinking before writing
- `prompts/engineer-perspective.md` - Technical review lens
- `prompts/executive-perspective.md` - Business value review lens
- `prompts/ux-perspective.md` - User needs review lens

### Outputs
- `outputs/` - Where your generated documents get saved

## Try It Out

### Example 1: Write a PRD with Multi-Perspective Review

```
Help me write a PRD for AI-powered task recommendations.

Use these files:
@context/product-overview.md
@context/company-strategy.md
@context/user-research-ai.md
@templates/lennys-prd-template.md
@prompts/socratic-questions.md

Before writing anything, ask me clarifying questions using the Socratic framework.
```

After answering the questions:

```
Based on my answers, write the PRD using the Lenny template structure.
Save it to outputs/ai-task-recommendations-prd.md
```

Then get multi-perspective feedback:

```
Review @outputs/ai-task-recommendations-prd.md from three perspectives:

1. Use @prompts/engineer-perspective.md - technical feasibility
2. Use @prompts/executive-perspective.md - business value
3. Use @prompts/ux-perspective.md - user needs

Give me feedback from each angle.
```

## What You'll Learn

This demo shows you:
- How persistent context makes every task faster
- How frameworks (Socratic questions) sharpen thinking
- How multi-perspective review catches blindspots
- How a simple folder structure becomes a Product OS

## Build Your Own

Ready to create one for YOUR company? Use the blank template that guides you through setup:

https://github.com/[username]/template-product-os
