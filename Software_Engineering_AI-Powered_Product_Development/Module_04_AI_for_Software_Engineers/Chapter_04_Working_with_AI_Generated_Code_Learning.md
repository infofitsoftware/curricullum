# Chapter 4: Working with AI-Generated Code

## Learning Objectives

By the end of this chapter, you should be able to:

1. Read AI-generated code with a review checklist.
2. Explain why “it runs once” is not enough.
3. Use AI for debugging without surrendering ownership.
4. Detect common AI code failure patterns.
5. Practice the verify-before-commit habit.

---

## 1. Why This Matters

AI can generate code faster than you can read it.  
That is exactly the danger.

Interviewers and team leads will ask:

> “Explain this function.”  
> “What happens if input is empty?”  
> “Why this approach?”

If your answer is “AI wrote it,” you are not yet an AI-powered engineer — you are an AI passenger.

**Course outcome reminder:**  
Use AI as assistant, not autopilot.

---

## 2. Reading AI-generated code (checklist)

Before accepting any AI snippet, ask:

1. **What is the input?**  
2. **What is the output?**  
3. **What are the steps?**  
4. **What can fail?**  
5. **Any security issue?** (secrets, injection, auth bypass)  
6. **Any dependency I don’t recognize?**  
7. **Does this match our MVP scope?**  

**Activity (15 min):**  
Teacher pastes a short AI-looking function with a subtle bug.  
Students review in pairs using checklist. Then reveal bug.

---

## 3. Understanding before using

### Rule
If you cannot explain the code in simple words, do not commit it.

### Practical method

1. Ask AI: “Explain this line by line at beginner level.”  
2. Re-explain yourself without looking.  
3. Change one variable name and predict effect.  
4. Run a failing test case on purpose.

**Discussion (5 min):**  
Is using AI to explain code “cheating,” or is it a learning accelerator when paired with re-explanation?

---

## 4. AI debugging workflow

### Good debugging prompt pattern

> Context: [stack]  
> Expected: [...]  
> Actual: [...]  
> Error: [exact message]  
> Code: [minimal snippet]  
> Ask: likely causes (top 3) + minimal fix + how to verify

### Bad debugging habit

> “Broken. Fix.” + entire repository dump + 20 regenerations

### Human remains owner

AI suggests causes.  
You reproduce, test, and confirm.

**Teacher demo:**  
Break a small page intentionally. Debug with AI live. Show verification.

---

## 5. Common AI code failure patterns

| Pattern | What you see | What to do |
|---------|--------------|------------|
| Hallucinated API | Import/package doesn’t exist | Verify docs before install |
| Outdated syntax | Old framework patterns | Confirm current version |
| Silent edge-case bugs | Works on happy path only | Test empty/invalid inputs |
| Over-engineering | Extra classes/files unneeded | Cut to MVP |
| Security slips | Secrets in code, weak validation | Remove/rotate; add checks |
| Scope creep | Extra features you didn’t ask | Reject and re-constrain |

---

## 6. Interactive lab (recommended)

Students bring one tiny task from their MVP:

1. Generate with AI.  
2. Review with checklist.  
3. Run it.  
4. Break one input.  
5. Fix.  
6. Write 5-line explanation in notebook.

No giant features. Focus on process quality.

---

## 7. Interview Preparation

**Q: How do you review AI code?**  
Check inputs/outputs, failure modes, security, dependencies, and whether it meets acceptance criteria; then test.

**Q: How do you debug with AI?**  
Provide expected/actual/error/minimal code; evaluate suggestions; verify by reproduction.

**Q: When do you reject AI output?**  
When unexplained, insecure, out of scope, or unverified.

---

## 8. Exit Ticket

Paste/write 8–12 lines of AI-generated code (or teacher-provided sample) and write:

* what it does;  
* one risk;  
* one test you would run.

**Next:** Responsible AI — ethics, safety, and professional use.
