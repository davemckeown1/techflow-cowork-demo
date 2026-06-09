# TechFlow Solutions: A Cowork Project for Leadership Coaching

A reference example for setting up Cowork as a working surface for ongoing leadership coaching. Built around a fictional Director of Engineering. The structure matters more than the persona.

## What this is

A worked example of how to organize a Cowork project around a specific person, the people around them, and a recurring set of work domains. You can run the demo as-is, or take the structure and build your own.

## Two paths

### Path 1. Run the demo as-is

1. Download the folder and open it in Cowork (or the chat version of Claude with file access).
2. Open `GEN AI COURSE PROMPTS CLAUDE COWORK.pdf` (or `GEN AI COURSE PROMPTS_CLAUDE CHAT.pdf` if you are not in Cowork). The project instructions are at the top of the file; the prompts follow.
3. Paste the project instructions into your project's settings.
4. Open a new conversation and start with:
Read everything in this project and commit anything you need to memory before we start.
5. Work through the prompts in order. Each one builds on what came before.

Recommended model: Claude Sonnet 4.6.

### Path 2. Build your own

Steal the structure for your own context. Coaching, advising, managing a domain, running an operating rhythm. The pattern works anywhere the work recurs and the people stay roughly the same.

How to adapt:

- Replace `_Context/` with your own. Write a role file, a voice/style file, and a stakeholder file. Keep them as raw data, not conclusions.
- Rename or replace the numbered folders to match the domains of your work.
- Write your own project instructions. Keep them short and focused on behavior (where to save things, when to push back, what to cite).
- Write your own prompts to walk through the work you actually do.

## Folder structure

```
.
├── _Context/                                # Raw inputs the assistant reads first
│   ├── 00_role_and_priorities.md
│   ├── 01_voice_and_style.md
│   ├── 02_stakeholders.md
│   └── TechFlow_Engineering_Dashboard.html
├── 01 — Weekly Meeting Prep/                # One folder per domain of work
├── 02 — SMART Goals/
├── 03 — Conflicting Priorities/
├── 04 — Delegation/
├── 05 — Coaching/
│   └── Alexa_1on1_Notes_Sarah.docx          # A living working file the assistant references
├── 06 — Constructive Feedback/
├── 07 — Accountability/
├── 08 — 30-Day Action Plan/
├── GEN AI COURSE PROMPTS CLAUDE COWORK.pdf  # Project instructions + prompts (Cowork)
├── GEN AI COURSE PROMPTS_CLAUDE CHAT.pdf     # Project instructions + prompts (Claude Chat)
└── README.md
```

Three components do the work. `_Context/` holds raw data. The numbered folders are where deliverables land. The prompts file holds the behavior layer (project instructions) and the example sequence.

## Design principles worth borrowing

- **Context is data, not conclusions.** Put facts and observations in context files. Leave the diagnoses and recommendations for the assistant to make.
- **Project instructions hold behavior.** Where to save, how to format, when to push back, what to cite. Keep them separate from domain data.
- **Voice is a first-class artifact.** Name how you talk and what you reject, and the assistant will match it.
- **Prompts ask questions of the context. They do not re-paste it.** "Given what you know about my workload" is stronger than listing the workload again.
- **One living working file per relationship that matters.** A running notes file accumulates over time and lets the assistant reason across patterns.

## A note on dates

This project is anchored to the week commencing June 8, 2026. If you run it much later, the dated content in `_Context/` will read as stale. Either update the dates first, or use the staleness to demonstrate the assistant catching context drift.
