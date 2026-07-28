# Chapter 3: Prompt Engineering for Developers

## Learning Objectives

By the end of this chapter, you should be able to:

1. Explain prompt engineering as a **developer skill**, not a separate career course.
2. Write prompts with clear instructions, context, and constraints.
3. Prompt for code generation, explanation, and refactor tasks.
4. Iterate prompts instead of blind regeneration.
5. Connect prompting to tokens/context cost control.

---

## 1. Scope reminder (important)

This module is **AI for software engineers**.

We teach prompt engineering because it improves:

* code quality;
* debugging speed;
* token efficiency;
* collaboration with AI tools.

We are **not** turning this into a full-time prompt marketing/copywriting program.

---

## 2. What is prompt engineering?

**Prompt engineering definition:** The practice of writing clear inputs to AI systems so outputs are useful, accurate, and constrained.

For developers, a prompt is like a ticket to a very fast junior teammate:

* vague ticket → messy PR  
* clear ticket → useful draft  

---

## 3. Developer prompt building blocks

Use this practical checklist (CCTO+):

| Block | Meaning | Example |
|-------|---------|---------|
| **C**ontext | Stack, file, user goal | “Flask beginner app, booking form page” |
| **T**ask | Exact ask | “Add server-side validation for email + date” |
| **C**onstraints | Limits | “No new libraries; keep function under 40 lines” |
| **O**utput | Format | “Show patched code + 3 test cases” |
| **+** Checks | Quality bar | “List assumptions; do not invent APIs” |

---

## 4. Writing clear instructions

### Weak
> Fix my code.

### Better
> In `register.js`, submit does nothing. Console: `Cannot read properties of null`. Here is the function. Find cause and give minimal fix.

### Stronger (spec-flavored)
> **Goal:** Form submit should validate email and show error under field.  
> **Stack:** HTML + vanilla JS.  
> **Constraint:** No frameworks.  
> **Output:** Updated function only + brief cause explanation.

**Activity (12 min):**  
Students rewrite 3 weak prompts from the board into strong ones. Peer swap.

---

## 5. Providing context and constraints

### High-value context

* relevant code snippet (not whole monorepo by default);
* exact error message;
* expected vs actual behavior;
* framework/language version if relevant;
* security constraints (“don’t log passwords”).

### High-value constraints

* “beginner-friendly”;
* “no new dependencies”;
* “keep public API unchanged”;
* “mobile-first HTML only”;
* “ask one clarifying question if blocked.”

**Token tip:**  
More relevant context > more total context.

---

## 6. Prompting AI to generate code (patterns)

### Pattern A — Greenfield small feature
> Create a single HTML page with event title, date, and register button. Semantic HTML, no CSS frameworks.

### Pattern B — Modify existing code
> Update only `saveBooking()` to reject past dates. Keep other functions unchanged. Show diff-style explanation.

### Pattern C — Tests first
> Given this function, propose 5 edge cases and write starter tests. Do not change production code yet.

### Pattern D — Explanation before edit
> Explain what this function does in 5 bullets. Then suggest one safer version.

**Teacher demo:**  
Run weak vs strong prompt in Cursor/Claude/ChatGPT and compare.

---

## 7. Iteration strategy (professional)

Do not spam “try again.”

Better iterations:

1. “Your solution uses library X — rewrite without it.”  
2. “Add error handling for empty input.”  
3. “Now optimize readability; no behavior change.”  

Each iteration should have a **single improvement goal**.

---

## 8. Common mistakes

1. No constraints → AI overbuilds.  
2. No stack info → wrong framework assumptions.  
3. Pasting secrets.  
4. Asking for production-ready auth/payments in one shot.  
5. Accepting first answer without running it.

---

## 9. Interview Preparation

**Q: What makes a good developer prompt?**  
Clear context, task, constraints, output format, and verification intent.

**Q: How do prompts affect cost?**  
Clear prompts reduce retries and huge irrelevant context, lowering token use.

---

## 10. Exit Ticket

Submit one strong prompt for a feature from your MVP must-have list (no need to run it yet).

**Next:** Working with AI-generated code — read, understand, debug.
