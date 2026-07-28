# Lesson 04 — Files, Folders, Terminal, Localhost & Ports

**Duration:** 60–75 minutes  
**Prerequisite:** Lessons 02–03  
**Goal:** Students can organize a project folder, run basic terminal commands, explain localhost and ports.

---

## 1. Why this lesson matters

Professional developers don’t only “click icons.” They:

- Organize code in **files and folders**  
- Run commands in a **terminal**  
- Test apps on **localhost** before going live  
- Know which **port** their app uses  

Today is your first step toward working like a real developer.

---

## 2. Files

A **file** is a named container for data on your computer.

| File | Holds |
|------|-------|
| `resume.pdf` | Your resume |
| `photo.jpg` | An image |
| `index.html` | Web page structure |
| `app.py` | Python program |
| `styles.css` | Styling rules |

**File extension** (the part after `.`) hints at the type:

- `.html` — web page  
- `.css` — styles  
- `.js` / `.ts` — JavaScript / TypeScript  
- `.py` — Python  
- `.json` — data in a standard format  

**Real-life analogy — notebook vs diary:**  
Each file is one notebook with a label on the cover (filename).

**Developer rule:** Use **clear names** — `booking-form.html` not `file1.html`.

---

## 3. Folders (directories)

A **folder** groups related files.

**Example — BookEase project (preview):**

```
bookease/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
    └── logo.png
```

**Real-life analogy — almirah drawers:**  
Shirts in one drawer, socks in another. Messy room = messy project = hard to find bugs.

**Paths:**

- **Relative path:** `css/style.css` (from inside project folder)  
- **Absolute path:** `C:\Users\Student\Projects\bookease\index.html` (full address on disk)

---

## 4. Terminal (command line)

The **terminal** is a text interface where you type **commands** instead of clicking.

**Why developers use it:**

- Start web servers (`npm run dev`)  
- Install tools (`pip install fastapi`)  
- Use **Git** (`git status`, `git commit`)  
- Navigate folders faster on servers (cloud has no desktop icons)

**Opening terminal:**

| OS | How |
|----|-----|
| Windows | PowerShell or “Terminal” in Cursor (`Ctrl + `` ` ``) |
| Mac | Terminal app or Cursor integrated terminal |

**Real-life analogy — voice commands to assistant:**  
Short phrases that do one job fast.

---

## 5. Essential terminal commands (beginner set)

Practice these in a folder called `practice` on your Desktop or Documents.

### Windows (PowerShell) and Mac/Linux

| Task | Windows (PowerShell) | Mac/Linux |
|------|----------------------|-----------|
| Where am I? | `pwd` or `Get-Location` | `pwd` |
| List files | `dir` or `ls` | `ls` |
| Change folder | `cd Documents` | `cd Documents` |
| Go up one level | `cd ..` | `cd ..` |
| Make folder | `mkdir practice` | `mkdir practice` |
| Make empty file | `New-Item notes.txt` | `touch notes.txt` |
| Clear screen | `cls` | `clear` |

**Tip:** Tab key auto-completes folder names.

**Technology example:** When you run a React app, the terminal shows:

```
Local:   http://localhost:3000
```

You didn’t click a `.exe` — you ran a **command**, and the terminal told you where to open the browser.

---

## 6. Localhost

**Localhost** = **this computer**, acting as a server during development.

- Special IP: `127.0.0.1` (always means “my machine”)  
- URL: `http://localhost` or `http://127.0.0.1`

**Real-life analogy — dress rehearsal:**  
The play runs in the school hall before the public show (deploy to cloud).

**Technology example:**

| Stage | URL | Who can see |
|-------|-----|-------------|
| Development | `http://localhost:3000` | Only you |
| Deployed | `https://bookease.yourname.com` | Everyone on internet |

**Common beginner mistake:** Sharing `localhost` link with a friend — it only works on **your** laptop.

---

## 7. Ports

A **port** is a **numbered door** on a computer. Many programs can run on one machine; each listens on a different port.

**URL format:** `http://localhost:3000`  
- `localhost` = which computer  
- `3000` = which program (door)

| Port | Typical use |
|------|-------------|
| 80 | HTTP websites |
| 443 | HTTPS (secure) websites |
| 3000 | React / Node dev server |
| 8000 | Python / FastAPI dev server |
| 5432 | PostgreSQL database |

**Real-life analogy — apartment building:**  
One building address (IP/domain), many flat numbers (ports).

**Technology example — full stack on your laptop:**

- Frontend: `localhost:3000`  
- Backend API: `localhost:8000`  
- Database: `localhost:5432`  

Three services, three ports, one computer.

---

## 8. How this connects to Lesson 03

| Internet (production) | Your laptop (development) |
|-----------------------|---------------------------|
| Domain `flipkart.com` | `localhost` |
| DNS → public IP | `127.0.0.1` |
| Server in data center | Your dev server process |
| Port 443 (HTTPS) | Port 3000 / 8000 |

Same ideas — different scale.

---

## 9. Cursor / VS Code file tree (5 min demo)

Show students in the IDE:

1. **Explorer** panel = folder tree  
2. Right-click → New File / New Folder  
3. Integrated **terminal** at bottom  
4. Open folder: `File → Open Folder` for a project  

**Developer workflow:**

```
Open project folder → edit files → run command in terminal → test in browser at localhost:PORT
```

---

## 10. Class activity — build folder structure (10 min)

Create this structure (terminal or IDE):

```
my-first-project/
├── README.md
├── index.html
└── assets/
    └── .gitkeep
```

`README.md` = short note: “My first developer project — [Your Name]”

---

## 11. Key takeaways

1. **Files** store code; **folders** organize projects.  
2. **Terminal** runs commands — essential for real dev work.  
3. **Localhost** = test on your machine before deploy.  
4. **Port** = which service on that machine (`:3000`, `:8000`).  
5. Good structure early saves pain later (BookEase will grow large).

---

## 12. Preview

Next topics in Week 1: **Cursor setup**, **GitHub**, and **AI-assisted coding** — you’ll use terminal + folders every day.
