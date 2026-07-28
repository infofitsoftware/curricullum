# Hands-on Exercise 02 — Step-by-Step Solution

**For instructors / self-check after attempting the exercise.**

---

## Part 1 — Weak prompt (expected outcome)

**Prompt sent:**
> Make a website for booking.

**Typical AI problems (any 2 acceptable):**

1. **Wrong scope** — generates full multi-page site or React/Next.js when student needed simple HTML.  
2. **No project branding** — generic “BookingPro” instead of BookEase.  
3. **Includes CSS/JS/backend** — too much for beginner exercise.  
4. **Vague structure** — no clear hero vs features separation.  
5. **Too long** — hundreds of lines hard to review.

**Sample rating:** 2/5 — starting point only, not bootcamp-ready.

**Sample first lines of response (illustrative):**

```html
<!DOCTYPE html>
<html>
<head>
  <title>Online Booking System</title>
  <style>/* lots of CSS */</style>
</head>
...
```

---

## Part 2 — Strong CCTO prompt (model solution)

**Strong prompt:**

> Context: I'm a bootcamp beginner in Week 1 building BookEase, a salon and spa appointment booking product. I need HTML only — no CSS, JavaScript, or frameworks.  
> Task: Write a complete `index.html` file with one hero section: an h1 headline "Book your salon slot in minutes", a short supporting paragraph, and a button labeled "Book Now".  
> Constraints: Use semantic HTML5 (header, main, section). Maximum 40 lines in the file. English only. Button must be a real `<button>` element.  
> Output: Provide the full `index.html` in a single code block, then exactly 2 sentences explaining which semantic tags you used and why.

**Expected sample output (abbreviated):**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BookEase — Salon Booking</title>
</head>
<body>
  <header>
    <h1>BookEase</h1>
  </header>
  <main>
    <section aria-labelledby="hero-heading">
      <h2 id="hero-heading">Book your salon slot in minutes</h2>
      <p>Choose your stylist, pick a time, and confirm — no phone calls needed.</p>
      <button type="button">Book Now</button>
    </section>
  </main>
</body>
</html>
```

**Explanation (AI might add):**  
Uses `header`/`main`/`section` for structure. `h2` for hero title keeps one `h1` for site name in header.

**Typical rating:** 4/5 — usable with minor edits.

**Two follow-up fixes student might note:**

1. Add `footer` with copyright line manually.  
2. Adjust headline tone for local market / add `lang` attribute if bilingual site planned.

---

## Part 3 — Debug prompt (model solution)

> Context: Beginner HTML + JavaScript. I have a "Book Now" button that should show an alert when clicked.  
> Task: Diagnose and fix the error.  
> Error (exact): `Uncaught ReferenceError: bookNow is not defined`  
> Constraints: Minimal fix only; explain in 2 sentences max; no frameworks.  
> Output: Cause explanation, then corrected script snippet using addEventListener.

**Expected AI diagnosis (summary):**  
Function `bookNow` was called in HTML (`onclick="bookNow()"`) but never defined in a `<script>` tag, or script loads before DOM.

**Minimal fix pattern:**

```html
<button type="button" id="book-btn">Book Now</button>
<script>
  document.getElementById('book-btn').addEventListener('click', function () {
    alert('Booking flow coming soon!');
  });
</script>
```

---

## Part 4 — Reflection (sample strong answers)

1. **Weak vs strong:** Strong prompt gave BookEase-specific HTML with size limits; weak prompt was generic and oversized.  
2. **Best CCTO part:** **Constraints** stopped AI from adding React/CSS.  
3. **Lesson 09 rule:** Always run and read code before commit.  
4. **Commit without reading?** No — interviews require explanation; hidden bugs cost time.  
5. **vs cheating:** Using AI with understanding and reflection is learning; submitting unexplained copy is cheating.

---

## Instructor grading rubric (quick)

| Criterion | Points |
|-----------|--------|
| Weak prompt run + 2 problems | 25 |
| Strong CCTO + ratings | 35 |
| Debug prompt quality | 25 |
| Original reflection | 15 |
| **Total** | **100** |

Pass: ≥ 70 with reflection in student's own writing.

---

## Discussion questions (class debrief)

- Did anyone get React despite constraints? → Retry prompt with “HTML ONLY, reject frameworks”.  
- How does this relate to **vibe coding loop**? → Strong prompt = better DEFINE + PROMPT steps.
