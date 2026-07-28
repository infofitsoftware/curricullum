# Chapter 1: Artificial Intelligence Foundations

## Learning Objectives

By the end of this chapter, you should be able to:

1. Explain AI vs Machine Learning vs Generative AI in plain language.
2. Define LLM, model, tokens, and context window — and why developers care.
3. Recognize major model providers and example models used in 2026.
4. Explain how AI companies typically charge users (subscription vs usage/tokens).
5. Discuss why “bigger/newer model” does not automatically mean “always use it for every task.”

---

## 1. Why This Matters (for software engineers)

This is **not** an AI research degree.  
This is **AI for software engineering**.

You need these foundations so you can:

* choose tools intelligently;
* understand invoices and usage limits;
* write better prompts with the right context;
* avoid burning money/tokens on careless workflows;
* explain AI decisions in interviews like a professional.

**Teacher opener (3 min):**  
“If AI is free magic, why did Uber blow a yearly AI budget in months?”  
Hold the answer — we return after tokens & pricing.

---

## 2. What is Artificial Intelligence?

**AI (Artificial Intelligence):** Computer systems designed to perform tasks that usually need human intelligence — recognizing patterns, making predictions, generating language, recommending actions, etc.

### Everyday examples students already know

| Example | What AI is doing |
|---------|------------------|
| YouTube/Netflix recommendations | Predicts what you might watch next |
| Face unlock | Recognizes patterns in your face image |
| Spam filters | Classifies emails as spam/not spam |
| Google Maps ETA | Predicts travel time from data patterns |
| ChatGPT / Claude / Gemini chat | Generates text responses |

### AI is a big umbrella

```text
Artificial Intelligence (broad)
   └── Machine Learning (learn patterns from data)
         └── Deep Learning (neural networks)
               └── Generative AI (create new content)
                     └── LLMs (text/code generation models)
```

**Discussion (5 min):**  
Name one product you use that feels “smart.” Is it generative (creates new text/image/code) or predictive (recommends/classifies)?

---

## 3. What is Generative AI?

**Generative AI:** AI that **creates new content** — text, code, images, audio, video — based on patterns learned from training data.

| Generative AI | Not mainly generative |
|---------------|-----------------------|
| ChatGPT writing an email | Spam filter labeling mail |
| Cursor generating a function | Sorting numbers with a fixed algorithm |
| Image generators creating posters | Simple calculator |

**For developers:** Generative AI can draft code, tests, docs, and refactors — but it can also invent wrong APIs (“hallucinate”).

---

## 4. What is an LLM?

**LLM (Large Language Model):** A generative AI model trained on huge amounts of text/code so it can predict and generate language (including programming languages).

Simple analogy:

> An LLM is like an extremely well-read intern: fast, fluent, often helpful — but it does not truly “know” your project unless you give it context, and it can sound confident while being wrong.

### What LLMs are good at (software context)

* explaining code;
* drafting boilerplate;
* suggesting refactors;
* writing first-pass tests;
* converting requirements into starter implementations.

### What LLMs are weak at without help

* knowing your private business rules;
* guaranteeing security;
* replacing system design judgment;
* knowing latest private company docs unless provided.

---

## 5. What is a “model”? Real examples

**Model definition:** A specific trained AI system you can call (via chat app, IDE, or API).

Companies release **families** of models, often with size/speed/cost tradeoffs.

### Major providers (2026 landscape awareness)

| Provider | Well-known products/models (examples) | Notes for developers |
|----------|----------------------------------------|----------------------|
| **OpenAI** | GPT family (e.g., GPT-4.1 / GPT-5 class models), Codex-related coding agents | Strong general + coding ecosystem via ChatGPT/API |
| **Anthropic** | Claude family (Sonnet, Opus, Haiku tiers) | Strong reasoning/coding; Claude Code tooling |
| **Google** | Gemini family | Strong multimodal + Antigravity / Google Cloud path |
| Others you may hear | Meta Llama (often open-weight), Mistral, xAI Grok, etc. | Ecosystem awareness; not all needed day 1 |

**Important teaching point:**  
Exact version numbers change quickly (Opus 4.x, GPT-5.x, Gemini 3.x).  
Students should learn the **pattern**, not memorize one forever-fixed SKU list:

* **Flagship / higher reasoning** (often slower/costlier) — e.g., Claude Opus-class, top GPT-class  
* **Balanced daily driver** — e.g., Sonnet-class / mid GPT/Gemini  
* **Fast/cheap** — Haiku-class / Flash-class for quick tasks

**Teacher demo cue:**  
Open model pickers in ChatGPT / Claude / Gemini / Cursor and show the dropdown live.

### “Parameters” (definition-level, no math deep dive)

**Parameters:** Internal knobs/weights the model learned during training. Roughly: more parameters can mean more capacity — but bigger is not automatically better for every task once quality, speed, context, and cost matter.

For this course: know the word exists; do **not** become a research paper reader yet.

### Why companies keep releasing “higher” models

* better reasoning/coding benchmarks;
* longer context windows;
* lower hallucination on some tasks;
* competitive pressure;
* new multimodal abilities.

**Product-aware question:**  
“Does this new model improve *my workflow enough* to justify price/latency?”

---

## 6. Tokens — one of the most important developer concepts

**Token definition:** A small chunk of text the model reads/writes. Roughly, many English words split into ~1 token, but code/punctuation varies. Think: **pieces of text that cost money and fill context**.

Why tokens matter:

1. **Billing** often depends on tokens in + tokens out.  
2. **Limits** — every model/tool has usage caps.  
3. **Quality** — dumping huge irrelevant files wastes tokens and can dilute attention.

### Relatable example

You paste:

* a 2-line bug + error message → few tokens  
* your entire project zip as text → huge tokens, expensive, often worse results

**Class activity (8 min):**  
Estimate which request is more expensive:

A. “Explain this 15-line function.”  
B. “Here are 40 files; rewrite my architecture.”  

Discuss why B can explode cost.

---

## 7. Context & context window

**Context definition:** The information available to the model for this response — your prompt, attached files, chat history, tool outputs, system instructions.

**Context window definition:** The maximum amount of context (measured in tokens) a model can consider at once.

If you exceed useful context:

* older chat may be dropped/summarized;
* model may miss important details;
* answers degrade;
* costs rise.

### Developer mental model

```text
Good context = relevant files + error + goal + constraints
Bad context  = everything you ever wrote + no clear ask
```

**Discussion (5 min):**  
If your booking form is broken, what minimum context should you give AI?

Expected direction: file snippet, error text, expected behavior, stack (HTML/JS), what you already tried.

---

## 8. How AI companies charge (real pricing patterns)

Exact rupee/dollar numbers change — teach **models of charging**:

### Pattern A — Subscription plans
Pay monthly for access + included usage quota.  
Examples: ChatGPT Plus/Pro-style plans, Claude Pro/Max-style plans, Cursor Pro-style plans.

### Pattern B — Usage / token billing (API style)
Pay for tokens consumed (input + output), sometimes per million tokens.  
Heavy automation can become expensive fast.

### Pattern C — Hybrid
Subscription + extra usage overages / credits / rate limits.

### Pattern D — Seat licenses (companies)
Businesses buy seats for employees; still may have usage costs underneath.

**Key lesson for future professionals:**  
AI cost is now part of engineering budgeting — like cloud servers.

---

## 9. Real-world cost reality check (bridge to Ch 2)

Hold details for tools chapter, but plant the idea:

* Unlimited “just keep prompting” culture can destroy budgets.  
* Enterprises now add caps, dashboards, and tool standardization.

**Exit question:**  
“If tokens cost money, what habit should a junior developer build?”

Target answer: be specific, attach only needed context, verify before rerunning huge agent loops.

---

## 10. Interview Preparation

**Q: AI vs Generative AI?**  
AI is the broad field; generative AI creates new content like text/code/images.

**Q: What is an LLM?**  
A large model trained to predict/generate language, including code.

**Q: What are tokens?**  
Text chunks models process; they affect cost and context limits.

**Q: What is context window?**  
Max tokens of information a model can consider in one go.

**Q: Why might a team choose a cheaper/faster model?**  
For simple tasks where flagship cost/latency is unnecessary.

---

## 11. Quick Reference

| Term | One-liner |
|------|-----------|
| AI | Machines performing intelligent-like tasks |
| Generative AI | AI that creates new content |
| LLM | Large language model for text/code generation |
| Model | A specific trained AI system you call |
| Parameters | Learned internal weights/capacity knobs |
| Token | Billing/context text unit |
| Context | Info model can use now |
| Context window | Max context size |
| Subscription | Monthly access plan |
| Usage billing | Pay per tokens/requests |

---

## 12. Exit Ticket

1. Define token + context in your own words.  
2. Name 3 model providers.  
3. Give one example of expensive vs cheap AI usage.

**Next:** AI-assisted software development tools — Cursor, Claude Code, Codex, Antigravity — productivity, pros, and expensive mistakes.
