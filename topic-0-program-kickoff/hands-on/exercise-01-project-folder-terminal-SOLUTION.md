# Hands-on Exercise 01 — Step-by-Step Solution

**For instructors / self-check after attempting the exercise.**

---

## Solution Part A — Terminal commands

### Windows (PowerShell)

```powershell
cd $HOME\Documents
mkdir bookease
cd bookease
mkdir css, js, images, docs
New-Item index.html, README.md -ItemType File
New-Item images\.gitkeep -ItemType File
Get-Location
dir
cd css
cd ..
tree /F
```

**Expected `dir` output (similar):**

```
    Directory: ...\Documents\bookease

Mode    Name
----    ----
d-----  css
d-----  docs
d-----  images
d-----  js
-a----  index.html
-a----  README.md
```

### Mac / Linux (bash/zsh)

```bash
cd ~/Documents
mkdir bookease
cd bookease
mkdir css js images docs
touch index.html README.md
touch images/.gitkeep
pwd
ls -la
cd css
cd ..
find .
```

**Expected `find .` output (similar):**

```
.
./css
./js
./images
./images/.gitkeep
./docs
./index.html
./README.md
```

---

## Solution Part B — File contents

### `README.md`

```markdown
# BookEase
Author: Priya Sharma
Week 1 — Topic 0 setup exercise
```

*(Student replaces with their name.)*

### `index.html`

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

---

## Solution Part C — Command explanations

| Command | Purpose |
|---------|---------|
| `cd $HOME\Documents` / `cd ~/Documents` | Go to Documents folder |
| `mkdir bookease` | Create project root |
| `cd bookease` | Enter project |
| `mkdir css, js, ...` | Create subfolders |
| `New-Item` / `touch` | Create empty files |
| `Get-Location` / `pwd` | Print current path |
| `dir` / `ls` | List contents |
| `cd css` then `cd ..` | Enter subfolder, return to parent |
| `tree` / `find .` | Show hierarchy |

---

## Solution Part D — Localhost concept

**Question:** What port for React dev server later?  
**Answer:** **3000** (common default; `http://localhost:3000`).

**Note for instructor:** Opening `index.html` via `file://` is fine for this exercise. Explain that **localhost + port** is used when a **dev server process** is running (Week 2+).

---

## Final folder structure

```
bookease/
├── README.md
├── index.html
├── css/
├── js/
├── images/
│   └── .gitkeep
└── docs/
```

---

## Verification checklist (instructor)

1. Folder structure matches above.  
2. `index.html` opens in browser with “BookEase — Coming Soon”.  
3. Student oral check: explain difference between **file** and **folder**.  
4. Student oral check: what is **localhost**? (This computer as test server.)
