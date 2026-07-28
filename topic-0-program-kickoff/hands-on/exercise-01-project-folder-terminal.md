# Hands-on Exercise 01 — Project Folder & Terminal Basics

**Topic:** Lesson 04 (files, folders, terminal, localhost, ports)  
**Duration:** 30–45 minutes  
**Tools:** Cursor (or VS Code), integrated terminal  
**Submission:** Screenshot of terminal + folder tree; upload to LMS or share in class folder.

---

## Objective

Create a proper **BookEase starter folder** on your computer using the terminal and IDE, and demonstrate you can navigate and inspect it with commands.

---

## Scenario (real-life context)

You just joined a dev team. The team lead says:

> “Before we write code, set up your project folder the right way. Name it `bookease`, add the standard structure, and show me in terminal that you can move around it.”

This is exactly what happens on day one of many internships.

---

## Instructions

### Part A — Create the project (terminal)

1. Open **Cursor**.  
2. Open the integrated terminal (`` Ctrl + ` ``).  
3. Navigate to your Documents folder (or `Desktop`):
   - **Windows:** `cd $HOME\Documents`  
   - **Mac/Linux:** `cd ~/Documents`  
4. Create the main project folder: `mkdir bookease`  
5. Enter it: `cd bookease`  
6. Create subfolders:
   - **Windows PowerShell:**
     ```powershell
     mkdir css, js, images, docs
     ```
   - **Mac/Linux:**
     ```bash
     mkdir css js images docs
     ```
7. Create files:
   - **Windows:** `New-Item index.html, README.md -ItemType File`  
   - **Mac/Linux:** `touch index.html README.md`  
8. Create a placeholder in images (optional):
   - **Windows:** `New-Item images\.gitkeep -ItemType File`  
   - **Mac/Linux:** `touch images/.gitkeep`

### Part B — Add content (IDE)

1. In `README.md`, write 3 lines:
   ```markdown
   # BookEase
   Author: [Your Name]
   Week 1 — Topic 0 setup exercise
   ```
2. In `index.html`, add minimal content:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
     <meta charset="UTF-8" />
     <title>BookEase</title>
   </head>
   <body>
     <h1>BookEase — Coming Soon</h1>
   </body>
   </html>
   ```

### Part C — Terminal proof (commands)

From inside `bookease`, run and **screenshot the output**:

1. `pwd` (Mac/Linux) or `Get-Location` (Windows) — shows you are in bookease  
2. `dir` or `ls` — lists files and folders  
3. `cd css` then `cd ..` — enter and leave subfolder  
4. Optional: `tree` (Windows) or `find .` (Mac/Linux) — full structure  

### Part D — Localhost preview (concept check)

1. Right-click `index.html` → **Reveal in File Explorer** / open in browser.  
2. Note the address bar: `file:///...` — this is **not** localhost yet; that’s OK for today.  
3. In your notebook, write one sentence: **What port might we use later when we run a React dev server?** (Answer: `3000`)

---

## Success criteria

- [ ] Folder `bookease` exists with `css`, `js`, `images`, `docs`  
- [ ] `index.html` and `README.md` present with content  
- [ ] Screenshot shows terminal commands and listing  
- [ ] Student can explain `cd`, `mkdir`, and `pwd`/`ls` in own words  

---

## Common mistakes

| Mistake | Fix |
|---------|-----|
| Created files on Desktop, not in `bookease` | `cd bookease` first |
| `mkdir css js` fails on Windows | Use `mkdir css, js` in PowerShell |
| Opened single file instead of folder in Cursor | **File → Open Folder** → select `bookease` |

---

## Instructor notes

Pair struggling students with a buddy for terminal only — do not complete commands for them; narrate steps instead.
