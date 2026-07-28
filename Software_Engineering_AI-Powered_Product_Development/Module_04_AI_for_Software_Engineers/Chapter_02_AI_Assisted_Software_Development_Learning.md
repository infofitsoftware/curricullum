# Chapter 2: AI-Assisted Software Development

## Learning Objectives

By the end of this chapter, you should be able to:

1. Explain vibe coding vs spec coding and when each helps.
2. Describe Cursor, Claude Code, OpenAI Codex, and Google Antigravity at a practical level.
3. Explain how these tools are changing software industry workflows.
4. List real productivity benefits and real costs/risks (including enterprise budget cases).
5. State a professional rule: AI accelerates development; humans remain accountable.

---

## 1. Why This Matters

In 2025–2026, “Can you code?” is becoming:

> “Can you ship reliable software with AI assistance — without losing engineering judgment?”

Companies hire developers who can:

* use AI tools fluently;
* control cost;
* review AI output;
* still understand fundamentals.

This course trains that balance.

**Teacher note:** Download/demo tools live. Students watch workflows, not only slides.

---

## 2. Vibe Coding

**Vibe coding definition:** Building software by describing intent in natural language and iterating with AI (chat/agent) to generate and modify code quickly.

Typical loop:

```text
Describe → AI drafts → Run/test → Correct → Describe again
```

### Good vibe coding
* prototyping UI layouts;
* generating boilerplate;
* exploring options fast;
* learning by reading generated code.

### Bad vibe coding
* accepting code you cannot explain;
* skipping tests;
* no repository understanding;
* endless regenerate loops that burn tokens.

**Discussion (5 min):**  
“Have you ever copied an answer that ‘looked right’ and failed later?” Connect to vibe coding risk.

---

## 3. Spec Coding

**Spec coding definition:** Writing a clear specification (problem, users, requirements, constraints, acceptance criteria) before asking AI to implement.

This matches product thinking from Modules 2–3.

### Mini spec before code

* Objective  
* User  
* Inputs/outputs  
* Constraints (tech, security, scope)  
* Acceptance criteria  
* Out of scope  

Then prompt AI with the spec.

**Why it matters:**  
Better specs → fewer retries → lower token cost → better architecture alignment.

**Activity (10 min):**  
Take your Module 3 MVP story and write a 8-line spec. Do **not** generate code yet.

---

## 4. AI productivity (realistic)

AI can increase speed on:

* boilerplate;
* repetitive refactors;
* test stubs;
* documentation drafts;
* explaining unfamiliar code.

AI does **not** automatically increase product value if you build the wrong thing faster.

**Product-aware reminder:**  
Speed without user outcome is just expensive motion.

---

## 5. The tool landscape (teacher demo chapter)

These tools overlap, but form factors differ.

### A) Cursor (Anysphere)

**What it is:** An AI-first code editor (IDE experience; VS Code–familiar), designed for daily coding with chat, inline edits, multi-file agents/composer-style workflows.

**Why developers like it:**

* stays inside the project;
* can use multiple model providers (model-agnostic depending on plan/setup);
* strong for everyday edit/refactor loops.

**Teacher demo ideas:**

1. Open a sample folder.  
2. Ask Cursor to add a form validation.  
3. Show diff review before accepting.  
4. Show model picker if available.

### B) Claude Code (Anthropic)

**What it is:** An agentic coding tool centered on Anthropic’s Claude models — commonly used as a terminal/CLI-first (and ecosystem-connected) coding agent that can read/modify repos, run commands, and work through tasks with approval gates.

**Why developers like it:**

* strong reasoning on complex tasks;
* good for repo-scale changes when guided well;
* popular in professional engineering teams.

**Teacher demo ideas:**

1. Run a simple “explain this folder” task.  
2. Ask for a small safe change.  
3. Show permission/approval behavior before destructive actions.

### C) OpenAI Codex (OpenAI)

**What it is:** OpenAI’s coding agent ecosystem (often accessed through ChatGPT plans / Codex surfaces — cloud agent, CLI/extensions depending on current packaging). Oriented to delegated coding tasks in the OpenAI ecosystem.

**Why it matters:**

* huge distribution through ChatGPT user base;
* convenient if team already pays for OpenAI;
* useful for cloud-delegated tasks and coding assistance.

**Teacher demo ideas:**

1. Show where Codex appears in ChatGPT/developer surfaces.  
2. Assign a small isolated task and review output.

### D) Google Antigravity

**What it is:** Google’s agent-first coding platform/IDE direction (including desktop/agent workflows powered significantly by Gemini models; evolving into broader agent surfaces). Positioned around agentic multi-step development workflows.

**Why it matters:**

* Google/Gemini ecosystem path;
* often attractive for experimentation / preview access economics;
* represents “agent-first” industry direction (plan → act → verify).

**Teacher demo ideas:**

1. Show agent-style task planning.  
2. Contrast with Cursor’s IDE feel and Claude Code’s CLI feel.

### Quick comparison table (classroom poster)

| Tool | Maker | Typical feel | Model center of gravity |
|------|-------|--------------|-------------------------|
| Cursor | Anysphere | AI IDE for daily coding | Multi-model options |
| Claude Code | Anthropic | Agentic coding (CLI-strong) | Claude (Opus/Sonnet/etc.) |
| Codex | OpenAI | ChatGPT/OpenAI coding agent path | GPT/Codex stack |
| Antigravity | Google | Agent-first Google workflow | Gemini-centered |

**Exact UI labels change — teach capabilities + judgment, not button memorization.**

Also mention awareness: GitHub Copilot / Copilot CLI (Microsoft/GitHub) is major in enterprises.

---

## 6. How these tools are shaping the industry

Observable shifts:

1. **From autocomplete → agents** that can plan and edit multiple files.  
2. **Smaller teams shipping faster** prototypes.  
3. **New skills demanded:** prompting, spec writing, review, eval, cost control.  
4. **New failure mode:** shipping plausible wrong code at scale.  
5. **Finance/ops involvement:** AI spend becomes a line item like cloud.

**Discussion (8 min):**  
Will AI replace junior developers?  
Guide class to: juniors who only paste die; juniors who verify/debug/product-think become more valuable.

---

## 7. Pros (with grounded examples)

| Benefit | Example |
|---------|---------|
| Faster boilerplate | Generate HTML form skeleton in minutes |
| Faster debugging start | Paste error + snippet, get likely causes |
| Learning accelerator | “Explain this function like I’m new” |
| Refactor assistance | Rename and update related files carefully with review |
| Test drafting | Generate first unit/manual test ideas |

---

## 8. Cons & hard real-world examples (do not skip)

### Cons list

* hallucinations (fake libraries/APIs);
* security leaks (secrets pasted into prompts);
* over-dependence / skill atrophy;
* messy PR quality if unreviewed;
* **token cost blowups** with agentic loops;
* company policy / tool lock-in changes.

### Case study 1 — Uber (budget overrun)

**What happened (2026 reporting):**  
Uber encouraged broad use of agentic coding tools (notably Claude Code/Cursor-class workflows). Adoption exploded. Usage-based AI costs scaled with that adoption. Uber reported burning through its **full-year 2026 AI budget in about four months**. Heavy sessions could be very expensive (reports included ~$1,200 in a short demo-like session). Leadership then moved to **caps/controls** (including per-employee/per-tool monthly limits in reporting) and more cost governance.

**Classroom moral:**  
High adoption ≠ free productivity. Without usage discipline, AI can become financially unsustainable.

### Case study 2 — Microsoft (Claude Code license rollback)

**What happened (May 2026 reporting):**  
Microsoft had expanded internal Claude Code access; it became very popular. Then Microsoft began **revoking/reducing many internal Claude Code licenses** (notably in Experiences + Devices), directing engineers toward **GitHub Copilot CLI**, with cutoff timing aligned to fiscal planning. Reasons discussed publicly/internally included standardization on first-party tooling and operating cost control — not “AI doesn’t work.”

**Classroom moral:**  
Enterprises optimize for **cost + control + strategy**, not only developer preference. Tools you love can be rotated by policy.

### Mini case discussion prompts

1. If your startup has ₹X/month AI budget, what rules would you set?  
2. Should companies rank employees by AI usage leaderboards? Why risky?  
3. What is the difference between productivity theater and real shipped value?

---

## 9. Professional workflow for this course

```text
1) Spec the task
2) Choose tool/model appropriate to task
3) Provide minimal high-quality context
4) Generate
5) Read diff
6) Run/test
7) Fix
8) Commit only what you understand
```

**Course rule reminder:**  
Manual-first on brand-new fundamentals; AI-second for acceleration; never on no-AI checks.

---

## 10. Interview Preparation

**Q: Vibe coding vs spec coding?**  
Vibe = conversational iteration; Spec = specify requirements first, then implement with AI.

**Q: Name AI coding tools and differences.**  
Cursor (AI IDE), Claude Code (Anthropic agentic coding), Codex (OpenAI coding agent path), Antigravity (Google agent-first platform).

**Q: Why can AI coding get expensive?**  
Token/usage billing + long agent loops + huge context dumps.

**Q: What did Uber/Microsoft cases teach?**  
Adoption without governance creates budget and strategy pressure.

---

## 11. Exit Ticket

1. One sentence: when you will use vibe coding.  
2. One sentence: when you will use spec coding.  
3. One risk from the Uber or Microsoft case in your own words.

**Next:** Prompt engineering for developers — practical, not a full PE degree.
