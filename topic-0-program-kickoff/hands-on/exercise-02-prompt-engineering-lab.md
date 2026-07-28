# Hands-on Exercise 02 — Prompt Engineering Lab

**Topic:** Lessons 07–08 (vibe coding, prompt engineering)  
**Duration:** 35–45 minutes  
**Tools:** Cursor AI chat **or** ChatGPT/Claude (free tier OK)  
**Submission:** Document with 3 prompt pairs + AI responses summary + your rating.

---

## Objective

Write **weak vs strong** prompts using the **CCTO** framework, run them in AI, and compare quality of outputs — without deploying code to production.

---

## Scenario (real-life context)

Your senior developer says:

> “Junior devs waste hours fixing vague AI output. Show me you can write one prompt that gets 80% right on the first try for a BookEase hero section.”

Recruiters in 2026 increasingly ask: *“How do you use AI in your workflow?”* This exercise is practice for that answer.

---

## Part 1 — Weak prompt experiment

1. Open AI tool (Cursor chat or browser).  
2. Send this **weak** prompt exactly:

   > Make a website for booking.

3. Copy the **first 10 lines** of the response (or summarize what it generated).  
4. Rate usefulness **1–5** (1 = useless, 5 = ready to use).  
5. Write **2 problems** with the output (e.g. wrong stack, too vague, no project name).

---

## Part 2 — Strong prompt (your CCTO)

Write and send a **strong** prompt that includes all four:

| CCTO | Your content |
|------|----------------|
| **Context** | BookEase, salon/spa booking, beginner HTML week, no frameworks |
| **Task** | Single `index.html` hero: headline, subtext, one CTA button “Book Now” |
| **Constraints** | Semantic HTML5 only, no CSS/JS, under 40 lines, English |
| **Output** | Code block only + 2-line explanation |

**Template (customize, don’t copy blindly):**

> Context: I'm a bootcamp beginner building BookEase (salon appointment booking). HTML only, no CSS/JS yet.  
> Task: Create the hero section markup for index.html with h1, p, and a button "Book Now".  
> Constraints: Semantic tags (header/section), max 40 lines total file, accessible button text.  
> Output: Full index.html in one code block, then 2 sentences explaining tags used.

5. Rate usefulness **1–5** again.  
6. Write **2 improvements** still needed (you’ll fix manually later — that’s normal).

---

## Part 3 — Debug prompt practice

Imagine this error (do not need a real broken file):

```
Console: Uncaught ReferenceError: bookNow is not defined
```

Write a **debug prompt** using CCTO (paste into AI optional — writing the prompt is the main task).

**Requirements:**

- Name stack (HTML + JavaScript beginner)  
- Paste exact error  
- Ask for cause in 2 sentences + minimal fix  
- Max 100 words in prompt  

Submit your debug prompt text even if you don’t run it.

---

## Part 4 — Reflection (5 sentences)

Answer in your own words:

1. What changed between weak and strong prompt results?  
2. Which CCTO part helped most?  
3. One rule from Lesson 09 you will follow when using AI.  
4. Would you commit AI output without reading? Why or why not?  
5. How is this different from cheating on homework?

---

## Success criteria

- [ ] Weak prompt submitted with rating + 2 problems  
- [ ] Strong CCTO prompt submitted with rating + 2 follow-up fixes  
- [ ] Debug prompt meets requirements  
- [ ] Reflection completed in own words  

---

## Academic integrity

- You may use AI to **generate** responses for Part 1–2.  
- **Reflection must be your own words.**  
- Do not share exact strong prompts with other students before submission (collaboration on reflection ideas OK).
