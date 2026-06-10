# Day 1 — IT Keywords, Web Basics & Course Kickoff

**Session goal:** Leave today knowing the **words**, the **big picture** of how apps work, **why this bootcamp exists**, and **how we use AI** — without pressure to code perfectly yet.

**How to use this sheet:** Six parts — core dev terms, how the web works, your laptop as a dev machine, more weekly keywords, the 6-month roadmap, and AI rules. Note each “remember this as…” line; we’ll go deeper every week.

---

## 1. Programming Language

**What it is:** A programming language is a special way of writing instructions that a computer can follow. Humans use English (or Hindi, etc.) to talk to each other; developers use programming languages to talk to machines.

**Simple analogy:** Like a recipe written in a specific format — “add 2 cups flour” becomes “print hello” or “save this user’s name.”

**Example:**
```text
print("Hello, world!")
```
This is one line of **Python**. The computer reads it and shows `Hello, world!` on the screen.

**Remember this as:** The **language** you choose to write your instructions in.

### Popular Programming Languages (know the names today)

| Language | Used for (brief) | You’ll see it in this course? |
|----------|------------------|-------------------------------|
| **Python** | Websites (backend), data, AI, automation, scripts | Yes — backend & APIs |
| **JavaScript** | Websites (frontend & backend), mobile apps | Yes — frontend & React |
| **TypeScript** | JavaScript with extra safety for large apps | Yes — with React |
| **HTML** | Structure of web pages (not a full programming language, but essential) | Yes — Week 2 |
| **CSS** | Look and layout of web pages | Yes — styling |
| **Java** | Android apps, enterprise software, banks | Mentioned in industry |
| **C / C++** | Games, operating systems, high-performance software | Mentioned in industry |
| **C#** | Windows apps, games (Unity), enterprise (.NET) | Mentioned in industry |
| **Go (Golang)** | Cloud services, fast backend systems | Mentioned in industry |
| **Rust** | Safe, fast systems programming | Mentioned in industry |
| **PHP** | Older/large number of websites (WordPress, etc.) | Mentioned in industry |
| **Ruby** | Web apps (Ruby on Rails) | Mentioned in industry |
| **Swift** | iPhone & Mac apps | Mentioned in industry |
| **Kotlin** | Android apps | Mentioned in industry |
| **SQL** | Talking to databases (“get all users named Raj”) | Yes — later in course |

**Takeaway:** Different languages exist for different jobs. Our bootcamp focuses mainly on **HTML, CSS, JavaScript, TypeScript, Python, and SQL** — the stack many companies hire for in 2026–2027.

---

## 2. Coding

**What it is:** Coding is the act of writing those instructions in a programming language. It is a **set of step-by-step commands** that tell the computer exactly what to do.

**Simple analogy:** Coding is like giving directions to a robot that takes everything literally — if you forget a step, it gets confused.

**Example:** “When the user clicks Login, check the password, then show the dashboard” becomes many lines of code in JavaScript or Python.

**Remember this as:** **Coding = writing the instructions.** Programming language = **which language** you write them in.

**Coding vs programming (quick note):** People often use both words the same way. In interviews, “I code in Python” and “I program in Python” mean the same thing for beginners.

---

## 3. Software / Application (App)

**What it is:** **Software** (also called an **application** or **app**) is any program that runs on a computer, phone, or server to do something useful for a user or a business.

**Simple analogy:** If coding is the recipe, software is the **finished dish** people actually use.

**Examples you already know:**
- **WhatsApp** — messaging app on your phone  
- **Google Chrome** — browser app  
- **Excel** — desktop app for spreadsheets  
- **Amazon website** — web application in the browser  
- **Instagram** — mobile app + website + backend working together  

**Types (names only — we cover these in Week 1):**
- Website, web app, mobile app, desktop app, SaaS (software you pay for monthly, like Netflix)

**Remember this as:** The **product** developers build. Your job path is to **build software** that solves real problems.

---

## 4. Frontend

**What it is:** The **frontend** is everything the user **sees and clicks** — buttons, colors, forms, menus, animations. It runs in the browser or on the device screen.

**Simple analogy:** The **face and counter** of a restaurant — what the customer experiences directly.

**Example:** The login page, product cards, and “Add to Cart” button on Flipkart are all frontend.

**Tech you’ll learn:** HTML, CSS, JavaScript, **React**, TypeScript.

**Remember this as:** **Frontend = what users see and interact with.**

---

## 5. Backend

**What it is:** The **backend** is the **behind-the-scenes** part users don’t see. It handles logic, security, saving data, sending emails, and talking to the database.

**Simple analogy:** The **kitchen and storage** of a restaurant — customers don’t go there, but nothing works without it.

**Example:** When you log in, the backend checks your password, creates a session, and fetches your orders from the database.

**Tech you’ll learn:** **Python**, **FastAPI**, PostgreSQL (database), authentication.

**Remember this as:** **Backend = brain and memory of the app** (server side).

---

## 6. IDE (Integrated Development Environment)

**What it is:** An **IDE** is the **app where developers write and edit code** — like Microsoft Word, but for programming. It highlights mistakes, suggests fixes, and often has a built-in terminal and Git tools.

**Simple analogy:** A **workshop** with all your tools in one place — hammer, screwdriver, and workbench together.

**Examples:**
- **VS Code** — very popular, free  
- **Cursor** — VS Code–based, with AI built in (we use this in the bootcamp)  
- **PyCharm** — popular for Python  
- **Android Studio** — for Android apps  

**Remember this as:** **IDE = where you write code every day.** We will set up **Cursor** in this course.

---

## 7. Cloud

**What it is:** The **cloud** means running your software on **someone else’s computers over the internet** (rented), instead of only on your laptop. You upload your app; users access it via a URL from anywhere.

**Simple analogy:** Renting a **shop space** instead of building your own building — you pay for what you use.

**Examples:** **AWS**, **Google Cloud**, **Microsoft Azure**, **Vercel**, **Netlify**.

**In this course:** You will deploy projects to the cloud (e.g. **AWS EC2**) so employers can open a **real live link**, not just “it works on my machine.”

**Remember this as:** **Cloud = your app living on the internet**, available 24/7.

---

## 8. GitHub

**What it is:** **GitHub** is a website where developers **store code online**, track every change (**version control**), and **collaborate** with teammates. It is also your **portfolio** — proof you can build real projects.

**Simple analogy:** **Google Drive for code**, with a full history of who changed what and when.

**Related word:** **Git** = the tool that tracks changes; **GitHub** = the popular website that hosts Git repositories.

**Example:** You push your BookEase project to GitHub; a recruiter opens your profile and sees your commits and README.

**Remember this as:** **GitHub = where your code lives publicly + how teams work together.** You will create a GitHub account in Week 1.

---

## 9. Port

**What it is:** A **port** is a **numbered door** on a computer where a specific program listens for traffic. When you run a website locally, you often open `http://localhost:3000` — **3000** is the port.

**Simple analogy:** A building has one address (IP / domain), but **many apartment numbers** (ports) — web server on 80, your dev app on 3000, database on 5432.

**Common ports (just recognize the numbers):**
| Port | Often used for |
|------|----------------|
| **80** | HTTP (normal website) |
| **443** | HTTPS (secure website) |
| **3000** | Local React / Node dev server |
| **8000** | Local Python / FastAPI dev server |
| **5432** | PostgreSQL database |

**Remember this as:** **Port = which “door” your app uses** on a machine. You’ll see `localhost:3000` and `localhost:8000` soon.

---

## Part 2 — How the Web Works

When you open a website, several invisible pieces work together. These four words explain that journey.

---

## 10. Browser

**What it is:** A **browser** is the app you use to open websites — **Chrome**, **Firefox**, **Edge**, or **Safari**. It reads code sent from the internet and turns it into the pages, buttons, and videos you see on screen.

**Simple analogy:** The **window** of a shop — you look through it; the real work happens inside (on servers).

**Example:** You type `amazon.in` in Chrome; the browser asks the server for Amazon’s page and displays it.

**Remember this as:** **Browser = where users view websites** (frontend runs here).

---

## 11. Server

**What it is:** A **server** is a powerful computer (often in a data center) that **stores and sends** websites, apps, and data when someone requests them. Your **backend** usually runs on a server.

**Simple analogy:** The **kitchen and warehouse** behind the restaurant — it prepares and delivers what the customer ordered.

**Example:** When you click “Login,” your browser talks to Amazon’s server, which checks your password and sends back a response.

**Remember this as:** **Server = a computer that serves your app or website to users.**

---

## 12. Domain

**What it is:** A **domain** is the **human-friendly name** of a website — like `google.com` or `bookease.com` — instead of a long number (IP address). You buy or rent a domain so people can find your project easily.

**Simple analogy:** A **shop signboard** on the street — easy to remember, points to your actual location.

**Example:** `github.com` is a domain; it takes you to GitHub’s servers on the internet.

**Remember this as:** **Domain = the name people type to reach your website.**

---

## 13. DNS (Domain Name System)

**What it is:** **DNS** is the internet’s **phone book**. When you type a domain, DNS finds the correct server IP address so your browser knows where to connect. It happens in milliseconds — you never see it, but nothing on the web works without it.

**Simple analogy:** You say “Rahul’s house” (domain); DNS looks up the exact flat number and building address (IP).

**Example:** You type `flipkart.com` → DNS returns something like `151.xxx.xxx.xxx` → browser connects to Flipkart’s server.

**Remember this as:** **DNS = translates domain names into server addresses.**

---

## Part 3 — Your Computer as a Developer Machine

Before your app lives on the cloud, you build and test it on **your own laptop**. These three ideas are daily tools.

---

## 14. Terminal (Command Line)

**What it is:** The **terminal** is a **text-based way to control your computer** — you type commands instead of clicking icons. Developers use it to run projects, install tools, and use Git.

**Simple analogy:** Talking directly to the computer in short commands, like texting instead of using a menu.

**Example:** `npm start` launches a React app; `git status` shows what files you changed.

**Remember this as:** **Terminal = type commands to run and control your code.** You’ll use it inside Cursor.

---

## 15. Files & Folders

**What it is:** **Files** are where code and data live (e.g. `index.html`, `app.py`). **Folders** (directories) organize files into a tree — like `src/`, `components/`, `styles/`. Every project is a folder structure.

**Simple analogy:** Files = individual documents; folders = drawers and cabinets that keep projects tidy.

**Example:** A React app might have `App.tsx` inside a `src` folder and `style.css` inside a `styles` folder.

**Remember this as:** **Files & folders = how every project is organized on disk.**

---

## 16. Localhost

**What it is:** **Localhost** means **“this computer”** — your own machine acting as a mini server while you develop. `http://localhost:3000` means “open the app running on my laptop, port 3000.” Only you can see it until you **deploy**.

**Simple analogy:** A **dress rehearsal** at home before the public show on the internet.

**Example:** You build BookEase on your laptop → test at `localhost:3000` → later deploy so anyone in the world can open it.

**Remember this as:** **Localhost = your app running on your machine for testing.**

---

## Part 4 — More Keywords You’ll Hear Every Week

---

## 17. Database

**What it is:** A **database** is organized **storage for app data** — users, orders, passwords (encrypted), posts. It keeps information safe and searchable even after you close the app. We use **PostgreSQL** in this course.

**Simple analogy:** A **filing cabinet with labels** — store millions of records and find any row in seconds.

**Example:** When you sign up on BookEase, your name and email are saved in a database table called `users`.

**Remember this as:** **Database = where app data lives permanently.**

---

## 18. API (Application Programming Interface)

**What it is:** An **API** is a **set of rules for how frontend and backend talk** — usually “send this request, get this JSON response.” When the React app fetches available time slots, it calls the BookEase API.

**Simple analogy:** A **waiter** — you (frontend) order; the waiter (API) takes the request to the kitchen (backend) and brings back the food (data).

**Example:** `GET /api/bookings` might return a list of bookings as JSON for the frontend to display.

**Remember this as:** **API = the messenger between frontend and backend.**

---

## 19. Git

**What it is:** **Git** is a **tool on your computer** that records every change to your code over time. You can undo mistakes, work on branches, and merge team work. **GitHub** is the website where Git repos are stored online.

**Simple analogy:** **Track changes on steroids** for code — full history, who changed what, and the ability to go back.

**Example:** You fix a bug → `git commit` saves a snapshot → push to GitHub so your teacher or teammate can see it.

**Remember this as:** **Git = version control on your machine; GitHub = Git repos on the internet.**

---

## 20. Full Stack

**What it is:** **Full stack** means you can work on **both frontend and backend** — the whole application, not just one side. A **full stack developer** builds the UI, the API, the database connection, and often helps deploy the app.

**Simple analogy:** Someone who can run **both the dining area and the kitchen** — not only serve food, but also cook it.

**Example:** You design the BookEase booking page (frontend), write the Python API (backend), and connect PostgreSQL (database) — that’s full stack work.

**Remember this as:** **Full stack = frontend + backend + database (+ often deploy).**

---

## 21. Deploy

**What it is:** **Deploy** means **putting your finished app on a server/cloud** so anyone with a URL can use it. Until you deploy, the app only exists on your laptop (`localhost`). Deployment is proof you can ship real software.

**Simple analogy:** **Opening your shop to the public** after practicing at home.

**Example:** BookEase runs on `localhost` during development → you deploy to AWS → share `https://bookease.yourname.com` in your portfolio.

**Remember this as:** **Deploy = go live on the internet.**

---

## Part 5 — Why This Bootcamp? (Your 6-Month Roadmap)

**What you’re joining:** A **6-month, project-based bootcamp** from zero coding to **job-ready full stack developer** — with modern AI tools used the way professionals use them today.

**BookEase in 5 lines:**
1. **BookEase** is a **booking platform** (like a simplified Calendly) — your main project through the course.  
2. You start with a **simple web page**, then add **styling**, **interactivity**, and rebuild it in **React**.  
3. You build a **Python/FastAPI backend**, **login system**, and **PostgreSQL database** behind it.  
4. You **test**, **containerize with Docker**, and **deploy live on AWS** with a real HTTPS URL.  
5. You finish with **HireLocal** — an AI-assisted capstone marketplace — plus a **GitHub portfolio** for interviews and freelance work.

**What you’ll be able to say on graduation day:** “I built and deployed full stack web apps with React, Python, PostgreSQL, Docker, AWS, Git, and AI features — here are the live links.”

**Remember this as:** **One long project (BookEase), many skills, two live products, one hireable story.**

---

## Part 6 — How We Use AI in This Course

AI (**Cursor**, **ChatGPT**, **Claude**) is part of how developers work in 2026 — but **you** are still the engineer. These rules keep learning honest and interview-proof.

### Rules in plain language

1. **AI suggests — you decide.** Read every line AI writes; if you can’t explain it, don’t ship it.  
2. **Manual first, AI second.** For new topics (HTML, loops, APIs), try yourself first — then use AI to improve or debug.  
3. **Verify everything.** Run the code, check the browser, fix errors yourself — don’t assume AI is correct.  
4. **No copy-paste without understanding.** Submitting code you can’t explain fails interviews and **no-AI skill checks** in this course.  
5. **Good prompts = good output.** Be specific: what you’re building, tech stack, constraints, and the format you want (e.g. “React component, TypeScript, mobile-first”).  
6. **AI is for speed, not shortcuts.** Use it like a senior dev reviewing your work — not a replacement for learning fundamentals.  
7. **When stuck:** try for 15 minutes → search the error → then ask AI with your code and error message attached.

**Remember this as:** **Human + AI = faster learning; human alone = hireable skill.**

---

## Quick Recap — One Line Each

| Term | Remember in one line |
|------|----------------------|
| **Programming language** | The language you write instructions in (Python, JavaScript, etc.) |
| **Coding** | Writing those instructions step by step |
| **Software / App** | The finished product users run or visit |
| **Frontend** | What users see and click |
| **Backend** | Hidden logic, data, and security on the server |
| **IDE** | Where you write code (Cursor / VS Code) |
| **Cloud** | Running your app on internet servers |
| **GitHub** | Online home for your code and portfolio |
| **Port** | Numbered door for a program on a computer |
| **Browser** | App that displays websites (Chrome, Edge, etc.) |
| **Server** | Computer that serves your app/data to users |
| **Domain** | Human-friendly website name (e.g. google.com) |
| **DNS** | Phone book that maps domains to server addresses |
| **Terminal** | Text interface to run commands on your computer |
| **Files & folders** | How code projects are stored and organized |
| **Localhost** | Your own machine as a test server |
| **Database** | Permanent storage for app data |
| **API** | How frontend and backend exchange data |
| **Git** | Tracks code changes on your machine |
| **Full stack** | Frontend + backend + database skills together |
| **Deploy** | Publishing your app live on the internet |

---

## How Everything Fits Together (big picture)

```text
User types DOMAIN (bookease.com)
        ↓
      DNS finds the SERVER address
        ↓
BROWSER loads FRONTEND (React)  ←→  API  ←→  BACKEND (Python/FastAPI)
                                              ↓
                                         DATABASE (PostgreSQL)

On your laptop (before deploy):
  IDE (Cursor) → FILES in FOLDERS → run in TERMINAL → LOCALHOST:PORT

When ready to go live:
  GIT commit → GITHUB → DEPLOY to CLOUD (AWS) → public URL for portfolio
```

---

## Day 1 Class Flow (suggested — 2 to 2.5 hours)

**Block A — What developers build (45 min)**
1. Welcome, session goal, and expectations — 5 min  
2. Programming language, coding, software/app — 20 min (live `print("Hello")` if possible)  
3. Frontend vs backend — 15 min (restaurant analogy)  
4. Full stack, database, API — 5 min (names only; details come later)

**Block B — Tools & the web (40 min)**
5. IDE, terminal, files & folders — 15 min (show Cursor folder tree + terminal)  
6. Browser, server, domain, DNS — 15 min (trace: type URL → what happens)  
7. Localhost, port, cloud, deploy — 10 min  

**Block C — How we work in this course (35 min)**
8. Git, GitHub — 10 min (show a real repo + commit history)  
9. 6-month roadmap & BookEase — 15 min  
10. AI rules in this course — 10 min  

**Block D — Close (15 min)**
11. Big-picture diagram walkthrough — 5 min  
12. Recap quiz — 10 min (random terms from recap table)

**Homework (optional):** Pick **10 terms** from the recap table and write one sentence each in your own words. Bonus: draw the big-picture diagram from memory.

---

## What Comes Next (rest of Week 1)

Tomorrow and this week you will:
- Set up **Cursor** and **GitHub** (hands-on)  
- Practice **terminal** basics and project **files & folders**  
- Build **“My First Web Page”** — your first step from words to real code  
- Start **BookEase** — your booking platform that grows every month

**You are not behind if you don’t understand everything today.** Every professional developer once sat exactly where you are — learning the words before learning the work.

---

*Aligned with Topic 0: Program Kickoff & Setup — AI-Powered Full Stack Developer Bootcamp*
