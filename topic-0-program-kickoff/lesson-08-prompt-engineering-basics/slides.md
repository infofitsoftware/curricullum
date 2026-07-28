# Lesson 08 — Prompt Engineering Basics

**Topic 0 | Week 1**

---

## Slide 1 — Title

# Prompt Engineering Basics
### Better prompts → better code → less rework

*AI is only as good as your instructions.*

---

## Slide 2 — What is it?

# Prompt engineering

Writing **clear instructions** so AI gives **useful** answers.

**Analogy:** Vague food order vs exact thali specs.

---

## Slide 3 — Weak vs strong

# Same task, different results

**Weak:** “Make a website.”

**Strong:** “HTML5 landing for BookEase salon: Hero + Features + Footer, semantic tags, no CSS yet, single `index.html`.”

---

## Slide 4 — CCTO framework

# Four parts of a dev prompt

| **C**ontext | What you're building + stack |
| **T**ask | Exact deliverable |
| **C**onstraints | Rules & limits |
| **O**utput | How AI should respond |

*Memorize: **CCTO***

---

## Slide 5 — Context

# Context

- Project name (BookEase)  
- Language / framework  
- What works vs what's broken  
- **Paste exact error text** when debugging  

🚫 No passwords or API keys

---

## Slide 6 — Constraints

# Constraints save time

- “Beginner level”  
- “No external libraries”  
- “Max 50 lines”  
- “Mobile-first CSS only”  

*Limits = fewer surprises.*

---

## Slide 7 — Output format

# Tell AI how to reply

- “Code block only”  
- “Code + 3 bullet explanation”  
- “Numbered steps then code”  

*Stops essay when you need a function.*

---

## Slide 8 — Debug prompt example

# Strong debug prompt

> React 18 + TS. Submit click fails. Console: `undefined preventDefault`. Paste component code. Explain cause in 2 sentences + minimal fix.

vs “It doesn't work.”

---

## Slide 9 — Iterate

# Follow-up prompts

1. Generate hero HTML  
2. Add accessibility (`alt`, labels)  
3. Suggest React component split later  

**Draft → feedback → draft 2**

---

## Slide 10 — Activity

# Prompt makeover

Rewrite weak prompts with **CCTO**:

- “Make login.”  
- “My CSS is broken.”  

*Pair share → class critique.*

---

## Slide 11 — Checklist

# Before you send

- [ ] Stack named?  
- [ ] One clear task?  
- [ ] Constraints set?  
- [ ] Output format set?  
- [ ] Secrets removed?  

---

## Slide 12 — Takeaways

# Remember

1. **CCTO** every serious prompt  
2. Specific beats vague  
3. Iterate & verify by **running** code  

**Next:** Manual vs AI-assisted rules
