# Lesson 03 — How the Web Works

**Duration:** 45–60 minutes  
**Prerequisite:** Lesson 02 (coding vs programming)  
**Goal:** Students can trace what happens when they type a URL and name browser, server, domain, and DNS.

---

## 1. Opening hook (5 min)

Open Chrome. Type `https://www.google.com` and press Enter.

Ask: “What happened in the last 2 seconds?”

Most students will say “Google opened.” Your job today is to show the **invisible steps** behind that one action.

---

## 2. What is the internet? (30-second version)

The **internet** is a global network of connected computers that send messages to each other using agreed rules.

**Real-life analogy — postal system:**  
Letters (data) travel between addresses (computers). Some addresses are homes (your laptop); some are big offices (servers at Google, Amazon, Flipkart).

You don’t need to understand cables and satellites today — just the **roles**: browser, server, domain, DNS.

---

## 3. Browser

**Browser** = the app you use to **view websites**.

| Browser | Company |
|---------|---------|
| Google Chrome | Google |
| Microsoft Edge | Microsoft |
| Mozilla Firefox | Mozilla |
| Safari | Apple |

**What the browser does:**

1. You type or click a link (URL).  
2. Browser **requests** the page from a server.  
3. Server sends back **HTML, CSS, JavaScript** (and images).  
4. Browser **renders** (draws) the page — buttons, text, videos.

**Real-life analogy — TV + remote:**  
You press a channel (URL); the TV (browser) receives the broadcast (web page) and displays it.

**Technology example:**  
When you open `flipkart.com`, Chrome doesn’t “store” Flipkart on your laptop — it fetches fresh data from Flipkart’s servers (unless some parts are cached).

**Frontend lives in the browser:** What you see and click is mostly drawn by the browser using code sent from the server.

---

## 4. Server

**Server** = a computer (often in a data center) that **waits for requests** and **responds** with data or web pages.

**“Client–server” model:**

| Role | Who | Example |
|------|-----|---------|
| **Client** | Your device + browser | You on laptop |
| **Server** | Remote powerful computer | Flipkart’s machines |

**Real-life analogy — restaurant:**  
You (client) order from the menu. Kitchen (server) prepares food and sends it out. You don’t go into the kitchen; you get the result at the table.

**What runs on servers:**

- Website files (HTML, images)  
- **Backend** code (Python, Node, Java)  
- **Databases** (user accounts, orders)  
- APIs (login, search, payment)

**Technology example — IRCTC:**  
When you search trains, your browser sends a request; IRCTC’s servers query the database and send back available trains as data the page displays.

---

## 5. Domain

**Domain** = the **human-friendly name** of a website.

Examples: `google.com`, `github.com`, `bookease.in`

**Why not just numbers?**  
Computers find each other using **IP addresses** — like `142.250.185.78`. Hard to remember. Domains are **memorable signboards**.

**Parts of a domain (simple):**

| Part | Example | Meaning |
|------|---------|---------|
| `www` | www.google.com | Subdomain (often optional) |
| `google` | google.com | Site name |
| `com` | google.com | TLD (commercial) |

**Real-life analogy — shop name on Main Street:**  
“Sharma Electronics” is easier than “Plot 47, Sector 12, GPS 28.6139° N…”

**Technology example:**  
Your bootcamp project will eventually have a domain like `yourname-bookease.dev` so recruiters can type a name, not an IP.

---

## 6. DNS (Domain Name System)

**DNS** = the internet’s **phone book**. It translates **domain name → IP address**.

**Step-by-step when you type `amazon.in`:**

1. Browser asks: “What IP is `amazon.in`?”  
2. **DNS resolver** (often your ISP or Google DNS) looks it up.  
3. DNS returns an IP address.  
4. Browser connects to that IP (Amazon’s server).  
5. Amazon’s server sends the page back.

**Happens in milliseconds** — usually invisible to you.

**Real-life analogy:**  
You say “Rahul’s house” (domain). DNS finds flat 402, Building B, Street address (IP).

**If DNS fails:** Browser shows “DNS_PROBE_FINISHED_NXDOMAIN” or “Can’t reach this site” — name not found in the phone book.

---

## 7. Full journey — one diagram to memorize

```
YOU type: https://flipkart.com
    ↓
BROWSER asks DNS: "What IP is flipkart.com?"
    ↓
DNS answers: "Use this IP address"
    ↓
BROWSER sends REQUEST to SERVER at that IP
    ↓
SERVER runs backend, reads database if needed
    ↓
SERVER sends RESPONSE (HTML, CSS, JS, images)
    ↓
BROWSER renders the page on your screen
```

**HTTPS:** The `s` means **secure** — data is encrypted in transit (important for login and payments). Port **443** is used (you’ll learn ports in Lesson 04).

---

## 8. Static vs dynamic (light touch)

| Type | What happens | Example |
|------|--------------|---------|
| **Static** | Server sends same files to everyone | Company “About Us” page |
| **Dynamic** | Server builds page per user/request | Gmail inbox, Flipkart cart |

Both use browser + server + domain + DNS. Dynamic pages need **backend** and often a **database**.

---

## 9. Class activity — “Trace the click” (10 min)

In pairs, fill this for **one app they use daily**:

1. **Browser** I use: ___________  
2. **Domain** I visit: ___________  
3. **Client** is: my phone / laptop  
4. **Server** is: owned by (company) ___________  
5. **DNS job:** converts domain to IP  
6. **One dynamic feature** on that site: login / search / feed / payment  

Share 2–3 answers with the class.

---

## 10. Common mistakes & interview soundbites

**Wrong:** “Websites are stored inside Chrome.”  
**Right:** “The browser **requests** pages from a **server**; DNS finds the server’s address.”

**Interview one-liner:**  
“When a user hits our domain, DNS resolves it, the browser talks to our server over HTTPS, and the server returns the frontend assets and API data.”

(You won’t say it perfectly on Day 1 — but you’ll grow into it.)

---

## 11. Key takeaways

1. **Browser** — displays the web (client).  
2. **Server** — serves pages and data (backend lives here).  
3. **Domain** — easy name for a site.  
4. **DNS** — maps domain → IP.  
5. Together they power every website and web app you use.

---

## 12. Preview next lesson

Next: **Files, folders, terminal, localhost, ports** — how developers work on a laptop *before* the app is on a server in the cloud.
