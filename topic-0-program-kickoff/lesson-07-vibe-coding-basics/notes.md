# Lesson 07 — Vibe Coding Basics

**Duration:** 45–60 minutes  
**Prerequisite:** Cursor installed (Lesson 05)  
**Goal:** Students understand “vibe coding,” when AI helps vs hurts, and the responsible workflow used in this bootcamp.

---

## 1. What is “vibe coding”?

**Vibe coding** (popular term in 2024–2026) means building software by **describing what you want in natural language** and letting **AI tools** (Cursor, ChatGPT, Claude) generate or edit code — while you guide, test, and correct.

**Not magic:** You still need to understand enough to **verify** output, **fix** errors, and **explain** your work in interviews.

**Real-life analogy — architect + contractor:**  
You describe the house (prompts); AI lays bricks fast (code); **you** inspect the structure before anyone lives in it.

**Technology example:**  
You type in Cursor: “Create a simple HTML page with a navbar and hero section for BookEase, a salon booking site.” Cursor generates files. You open the browser, check mobile view, fix spacing manually.

---

## 2. Tools you will use

| Tool | Role |
|------|------|
| **Cursor** | IDE with AI built in — edit code in your project |
| **ChatGPT / Claude** | Chat for explanations, debugging help, planning |
| **GitHub Copilot** | (Optional) inline suggestions in other editors |

**In this bootcamp:** **Cursor** is primary — code stays in your project folder with terminal and Git.

---

## 3. What vibe coding is good for

✅ **Starting faster** — boilerplate HTML, folder structure, repetitive code  
✅ **Learning** — “Explain this error like I’m 15”  
✅ **Refactoring** — “Rename this function and update all usages”  
✅ **Documentation** — README, comments (review before trusting)  
✅ **Debugging hints** — paste error + code snippet  

**Real-life example:**  
Student needs a responsive footer. AI generates 80% correct layout; student adjusts padding and verifies links — saves 30 minutes, still learns CSS.

---

## 4. What vibe coding is bad for

❌ **Blind copy-paste** without reading  
❌ **Skipping fundamentals** — “AI wrote it, I don’t know how it works”  
❌ **Secrets in prompts** — never paste API keys, passwords  
❌ **Trusting wrong answers** — AI can invent fake libraries or outdated syntax  
❌ **Cheating skill checks** — course includes **no-AI assessments**  

**Real-life example:**  
Student submits AI code that uses a non-existent npm package. Site fails in interview demo. **Root cause:** never ran `npm install` or read the imports.

---

## 5. The responsible vibe coding loop

Use this **every time**:

```
1. DEFINE  — What should this feature do? (one sentence)
2. PROMPT  — Clear request + tech + constraints
3. GENERATE — Let AI produce code
4. READ    — Line by line: do I understand the idea?
5. RUN     — Terminal + browser: does it work?
6. FIX     — You or AI — but YOU verify the fix
7. COMMIT  — Git commit with a message YOU wrote
```

**Analogy — tasting while cooking:**  
AI stirs the pot; you taste before serving guests.

---

## 6. When to use AI vs your brain

| Situation | Use AI? |
|-----------|---------|
| New syntax you haven’t practiced | Try 15 min yourself, then AI |
| Typo / obscure error message | Yes — paste error + code |
| Entire capstone without learning | No — fails interviews |
| Repetitive CSS grid | Yes — then verify responsive |
| Security (auth, payments) | AI draft OK — **you** must understand |

**Bootcamp rule:** **Manual first on new topics**, AI second for improvement.

---

## 7. Ethics & honesty

- **Disclose AI use** when asked by employer or client (many allow AI assist; few allow zero understanding).  
- **Your portfolio** must be code you can **walk through** line by line.  
- **Plagiarism** = copying another student’s or AI output without learning = same as copying homework.

**Interview reality:**  
“How does your login work?” — AI can’t answer for you in the room.

---

## 8. Live demo script (instructor)

1. Open empty folder in Cursor.  
2. Prompt: “Create index.html with title BookEase and a welcome paragraph.”  
3. Show generated file.  
4. Intentionally break something (delete closing tag).  
5. Show browser error.  
6. Ask AI to fix — then **explain** what was wrong.  

**Debrief:** AI fixed fast because **you** knew something was broken.

---

## 9. Class discussion (10 min)

**Prompt pairs:**

- Good vibe coder habit: ___________  
- Bad vibe coder habit: ___________  
- One thing I will always do after AI generates code: **RUN and TEST**

---

## 10. Key takeaways

1. **Vibe coding** = natural language + AI + **your judgment**.  
2. AI **accelerates**; it does not **replace** learning.  
3. Always: **prompt → generate → read → run → fix → commit**.  
4. Never paste secrets; never submit code you can’t explain.  
5. This bootcamp trains **human + AI** developers — the combination companies want in 2026.

---

## 11. Preview

Next lesson: **Prompt engineering basics** — how to write prompts that get useful code on the first try.
