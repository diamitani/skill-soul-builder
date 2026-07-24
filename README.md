# skill-soul-builder

![Category: Product & Architecture](https://img.shields.io/badge/category-Product%20%26%20Architecture-blue)
![Status: Active](https://img.shields.io/badge/status-active-brightgreen)

Give your AI agent a soul.

Most AI agents are stateless instruction-followers — they respond correctly but feel hollow, inconsistent, or off-brand. Soul-Builder fixes that. It takes a structured definition of personality, values, and behavior constraints and generates everything needed to inject a consistent "soul" into any running agent: a complete system prompt, behavior rules, response templates, and a personality matrix. The result is an agent that doesn't just answer questions — it has a voice, a set of non-negotiable guardrails, and a character that stays consistent across every interaction.

## What It Does

- Accepts an agent archetype (Hunter, Consultant, Analyst, or Advocate) plus brand voice parameters and generates a full soul definition package
- Produces a ready-to-inject `system_prompt.txt` with personality, tone, and operating principles baked in
- Outputs `behavior_rules.json` with hard constraints: daily limits, working hours, content guardrails, and retry logic
- Creates `response_templates.json` with pre-built objection handling scripts and meeting request patterns tuned to the agent's voice
- Runs a validation pass that checks for bias, tone consistency, and guardrail coverage — and outputs a `validation_report.json`

## How to Use

1. Define your agent's archetype and brand voice in the input schema (see `SKILL.md` for full schema)
2. Run the soul generation command via CLI or pass the schema directly to Claude with this skill loaded
3. The skill outputs a `soul_definition_{agent_name}/` directory with all files ready to use
4. Load `system_prompt.txt` as your agent's system prompt and `behavior_rules.json` as your constraint layer
5. Reference `integration_guide.md` inside the output package for wiring instructions

## Trigger Phrases

- "Give this agent a personality"
- "Define the soul for my agent"
- "Build a system prompt with guardrails"
- "Create a behavior definition for [agent name]"
- "Set the tone and values for this agent"
- "I want my agent to sound like a [hunter / consultant / analyst / advocate]"
- "Add content guardrails to my agent"
- "Generate a soul definition"

## Category

Product & Architecture

## Author: Patrick Diamitani

GTM AI & Automation Manager at Atlas HXM. Builds agent skills and automation systems for sales, marketing, and revenue operations teams.

---

> Built with Claude Code · Part of the [Patrick's Skills Library](https://github.com/diamitani)
