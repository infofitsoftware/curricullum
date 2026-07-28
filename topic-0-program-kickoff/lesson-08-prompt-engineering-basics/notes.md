# Lesson 08 — Prompt Engineering Basics

**Duration:** 45–60 minutes  
**Prerequisite:** Lesson 07 (vibe coding)  
**Goal:** Students can write clear prompts with context, constraints, and output format — and compare weak vs strong prompts.

---

## 1. What is prompt engineering?

**Prompt engineering** = the skill of writing **clear instructions** to AI so you get **useful, accurate** answers.

Bad prompt → wrong code, wasted time.  
Good prompt → 80% correct on first try, you polish the rest.

**Real-life analogy — ordering food:**  
“Something good” vs “One veg thali, less spicy, no onion, takeaway by 1 PM.” Specific order = correct plate.

**Technology example:**  
Weak: “Make a website.”  
Strong: “Create `index.html` for BookEase salon booking: semantic HTML5, sections Hero + Features + Footer, mobile-first, no CSS yet.”

---

## 2. The four parts of a strong dev prompt

Every good coding prompt should include:

| Part | What to include | Example |
|------|-----------------|---------|
| **Role / context** | What you’re building, stack | “BookEase landing page, HTML only, beginner project” |
| **Task** | Exact deliverable | “Add a contact form with name, email, message” |
| **Constraints** | Rules & limits | “No frameworks, max 80 lines, accessible labels” |
| **Output format** | How to respond | “Single file, code block only, brief comment on each section” |

**Memory phrase:** **CCTO** — Context, Task, Constraints, Output.

---

## 3. Weak vs strong prompts (side by side)

### Example A — HTML section

**Weak:**  
> Fix my page.

**Strong:**  
> I'm building BookEase (salon booking). In `index.html`, the Features section uses `<div>` everywhere. Refactor to semantic HTML (`section`, `h2`, `ul`) only for the Features block. Keep same visible text. Show only the updated section markup.

### Example B — Debugging

**Weak:**  
> It doesn't work.

**Strong:**  
> React 18 + TypeScript. When I click Submit, nothing happens. Console error: `Cannot read properties of undefined (reading 'preventDefault')`. Here is my `BookingForm.tsx` (paste code). Explain the cause in 2 sentences, then show the minimal fix.

### Example C — Learning

**Weak:**  
> Teach me JavaScript.

**Strong:**  
> I'm a beginner. Explain `const`, `let`, and `var` in JavaScript with one simple example each and when to use `const` in modern code. Max 150 words, no advanced topics.

---

## 4. Context — what to attach

Give AI **enough background**, not your life story.

**Include when relevant:**

- File name and language (`app.py`, Python 3.11)  
- Framework (React 18, FastAPI)  
- What already works vs what’s broken  
- Error message **copy-pasted exactly**  
- Screenshot description if UI bug  

**Don’t include:**

- Passwords, API keys, personal Aadhaar/bank data  
- Entire 500-file repo — attach **one file** or relevant snippet  

**Real-life analogy:** Doctor needs symptoms + history, not vague “I feel bad.”

---

## 5. Constraints that save you time

Useful constraints for coding prompts:

- “Beginner-friendly — no advanced patterns”  
- “No external libraries”  
- “Keep responsive using CSS flexbox only”  
- “Comments on non-obvious lines only”  
- “If unsure, ask one clarifying question before coding”  

**Technology example:**  
“Generate FastAPI endpoint `GET /health` returning `{"status": "ok"}` — no database, no auth, under 15 lines.”

---

## 6. Output format — be explicit

Tell AI **how** to answer:

| Goal | Output format instruction |
|------|---------------------------|
| Only code | “Reply with code block only, no preamble” |
| Code + explanation | “Code first, then 3 bullet explanation” |
| Step-by-step | “Numbered steps before final code” |
| Diff / patch | “Show only changed lines with file name” |

**Why it matters:** Stops AI from writing a 500-word essay when you need one function.

---

## 7. Iteration — follow-up prompts

First answer rarely perfect. **Iterate** like a conversation:

1. “Generate hero section HTML.”  
2. “Add `alt` text on images and improve button contrast for accessibility.”  
3. “Extract repeated card markup into a comment showing how I’d componentize later in React.”  

**Analogy — revision drafts:** Essay draft 1 → teacher feedback → draft 2.

---

## 8. Class exercise — prompt makeover (15 min)

Rewrite these weak prompts using **CCTO**:

1. “Make login.”  
2. “My CSS is broken.”  
3. “Explain database.”  

**Sample strong #1:**  
> Context: BookEase static HTML week, no JS yet. Task: Add a login **form UI only** (email, password, submit button) in a new `login.html` section — no backend. Constraints: semantic HTML, labels linked to inputs, mobile-friendly. Output: full `login.html` file.

Compare with partner; instructor picks 2 to critique.

---

## 9. Prompt checklist (printable)

Before sending a coding prompt, check:

- [ ] Did I name the **tech stack**?  
- [ ] Is the **task** one specific thing?  
- [ ] Did I add **constraints** (size, libraries, skill level)?  
- [ ] Did I specify **output format**?  
- [ ] Did I paste **errors/code** if debugging?  
- [ ] Did I remove **secrets**?  

---

## 10. Key takeaways

1. **Prompt engineering** = clear instructions → better code.  
2. Use **Context, Task, Constraints, Output (CCTO)**.  
3. Weak prompts waste time; strong prompts are a **hireable skill** in 2026.  
4. Iterate — first draft is a starting point.  
5. Always **verify** AI output by running it.

---

## 11. Preview

Next: **Manual coding vs AI-assisted coding rules** — official bootcamp policy so you stay interview-proof.
