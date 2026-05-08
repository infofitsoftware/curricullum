# THE MODERN SOFTWARE ENGINEER — ZERO TO SELF-RELIANT
## Complete 5–6 Month Live Training Curriculum
### For Absolute Beginners | Job-Ready | Freelance-Ready | Startup-Ready

---

> **One thread, one project, zero wasted sessions.**
> Every module builds a working piece of the same real product.
> Students deploy something live at the end of every single module.

---

## THE SPINE PROJECT: *BookEase* — Local Business Appointment Platform

Throughout the course, students build **BookEase** — a real, fully deployed web platform where local service businesses (salons, clinics, tutors, fitness trainers) can list their services and customers can book appointments online.

**Why this project?**
- Every small business needs this → real client potential from Day 1
- Naturally demands: frontend, backend, database, auth, AI, deployment
- Students can immediately pitch it as a freelance service
- Simple enough to build, complex enough to be impressive

---

---

# 1. COURSE OVERVIEW

| Attribute | Details |
|---|---|
| **Duration** | 24 Weeks (6 Months) |
| **Live Sessions** | 4 days/week × 2 hours = ~192 hours live |
| **Format** | Live teaching + Pair coding + Solo builds |
| **Target Audience** | Complete beginners — zero IT background |
| **Class Size** | 20–30 students (ideal for live coding) |
| **Language of Instruction** | Hindi/English (Hinglish) |

### End Outcomes — What Students CAN DO After the Course

| Track | Roles / Capabilities |
|---|---|
| **Employment** | Junior Frontend Developer, Junior Full Stack Developer, Junior Backend Developer, QA Tester, Technical Support |
| **Freelancing** | Build and deploy business websites, booking platforms, landing pages, REST APIs, chatbots for clients |
| **Entrepreneurship** | Launch a SaaS product, tech-enabled service startup, or AI-powered tool independently |

---

---

# 2. LEARNING ROADMAP (HIGH LEVEL)

```
PHASE 1 → PHASE 2 → PHASE 3 → PHASE 4 → PHASE 5 → PHASE 6
Web       Frontend   Backend    Full       Cloud &    AI & Career
Basics    Framework  & APIs     Stack      Deploy     Launch
(Wk 1-4)  (Wk 5-8)  (Wk 9-12) (Wk 13-16) (Wk 17-20) (Wk 21-24)
```

### How Each Phase Creates the Need for the Next

| Phase | What Students Build | What They Can't Do Yet | Why They Need the Next Phase |
|---|---|---|---|
| **Phase 1** | Static BookEase landing page — live on the internet | The page looks great but data is hardcoded. Nothing changes, nothing saves | Need dynamic, reactive UI |
| **Phase 2** | React-powered BookEase frontend — services list, booking form, animations | Form collects data but nothing is processed, stored, or validated on the server | Need a brain behind the UI |
| **Phase 3** | FastAPI backend with full REST API — bookings, business listings, user auth | APIs work but data is lost every time the server restarts | Need a real database |
| **Phase 4** | Full local stack — React + FastAPI + PostgreSQL running together | Only runs on my laptop. Clients can't use it. Nobody else can access it | Need to put it on the internet |
| **Phase 5** | BookEase deployed on AWS EC2 — live, public URL, CI/CD pipeline | Manual, repetitive, and has no intelligence. Can't scale | Need automation and AI |
| **Phase 6** | AI chatbot on BookEase + full capstone. Portfolio, resume, freelance profiles live | Ready for the world | Go earn |

---

---

# 3. DETAILED MODULE STRUCTURE

---

## MODULE 0: Orientation — How the Digital World Works
### Duration: Week 1 (4 sessions × 2 hours)

### Purpose
Do NOT skip this. Students who understand context learn 3× faster. This week answers: *"What is all of this, and why does it matter?"*

### Concepts Covered
- What is a computer, operating system, file system
- What is the internet — servers, clients, HTTP in plain English
- What is a website vs a web app vs a mobile app
- What is code — what does a developer actually do all day
- The modern developer toolkit: browser, terminal, VS Code, AI tools
- **What is Vibe Coding** — using AI as your co-pilot, not a crutch
  - Demo: Ask Claude to write a paragraph of code. Understand what it wrote. Ask it to explain.
- Introduction to AI tools: Cursor IDE, Claude, ChatGPT, GitHub Copilot
- How this course works — the BookEase project spine, the 6-month journey

### Tools Set Up This Week
- Install VS Code
- Install Cursor IDE
- Create accounts: GitHub, Claude.ai, ChatGPT, Hostinger (free trial)
- Browser dev tools intro (Chrome DevTools)

### Hands-on Activities
1. Open browser DevTools → inspect any website's HTML
2. Ask ChatGPT: *"Explain what a web server does like I am 10 years old"* — discuss the answer together
3. Use Cursor to generate 5 lines of HTML. Read it. Understand it. Edit one word manually.

### Deliverable
Students understand the landscape. They know the destination (BookEase). They are set up and ready to build.

### Deficiency Trigger
*"I want to create a webpage, but where do I even start?"*

---

---

## MODULE 1: Your First Website — Live on the Internet
### Duration: Weeks 2–4 (3 weeks)

### Real-World Project
**BookEase Landing Page** — A professional multi-section website for the BookEase platform with: hero section, features section, how-it-works section, testimonials, and a contact form. Deployed live with a real domain.

*Business context: This is exactly what a client would pay ₹15,000–₹50,000 for.*

---

### WEEK 2 — HTML: The Skeleton

#### Concepts Covered
- What is HTML and why it exists
- Tags, elements, attributes — the grammar of the web
- Essential tags: headings, paragraphs, links, images, lists, divs, sections
- Forms and inputs
- Semantic HTML — why it matters for Google (SEO intro)
- Inspect any real website's HTML live in class

#### Hands-on Activities
1. Manually type (not copy-paste) a 20-line HTML page
2. Build the BookEase landing page structure in pure HTML — just skeleton, no styling
3. Use Cursor AI to generate the "Features" section HTML → read every line together as a class, make 3 manual edits
4. **Vibe Coding drill**: Write a prompt for Cursor to generate a "testimonials" section. Review the output. Fix one thing manually.

#### Key Teaching Moment
Show the difference between AI-generated code and understanding what it does. Rule: *"If you can't edit one line of AI code by yourself, you don't own it."*

---

### WEEK 3 — CSS: Making It Beautiful

#### Concepts Covered
- What is CSS — separating style from structure
- Selectors, properties, values — the grammar
- Box model: margin, padding, border — THE most important concept in CSS
- Flexbox — the modern layout system (must-know)
- CSS Grid basics
- Colors, fonts (Google Fonts), spacing systems
- Responsive design — media queries, mobile-first thinking
- CSS variables for consistent design

#### Hands-on Activities
1. Style the BookEase HTML page manually — colors, fonts, spacing
2. Build a responsive navbar using Flexbox
3. Use Cursor to generate a CSS card component → edit the border-radius and color manually
4. **Vibe Coding drill**: Prompt Cursor: *"Make this section responsive for mobile"* → inspect what changed and why

#### Tools
- Google Fonts
- Coolors.co (color palette generator)
- CSS Tricks reference
- Cursor IDE

---

### WEEK 4 — JavaScript + Deployment

#### Concepts Covered
**JavaScript (Essentials Only)**
- What is JavaScript — making pages interactive
- Variables (let, const), data types, basic operators
- Functions — defining and calling
- DOM manipulation — selecting elements, changing text, toggling classes
- Event listeners — onclick, onsubmit
- Basic form validation with JS

**Deployment Concepts**
- What is a domain — DNS explained simply (domain → IP address → server)
- What is web hosting — shared hosting, VPS, cloud
- What is a file manager
- What is HTTPS / SSL

#### Hands-on Activities
1. Add a mobile menu toggle (hamburger menu) using pure JavaScript
2. Add form validation to the contact form — show/hide error messages
3. Use Cursor to generate a "smooth scroll to section" feature → test it → understand it
4. **DEPLOYMENT SESSION (the BIG moment):**
   - Create Hostinger account
   - Buy a domain (teacher demonstrates with real money, students use free subdomain)
   - Upload website files via Hostinger File Manager
   - Enable free SSL
   - **Website is LIVE at a real URL**
5. Register on Fiverr and Upwork — create profile, add "HTML/CSS Website Development" as skill
6. Start resume — add first skill set

#### Deliverable
**BookEase Landing Page** — live on the internet with a real domain, SSL, responsive on mobile.
Students share their live URL in the WhatsApp group.

#### Tools & Technologies
- HTML5, CSS3, Vanilla JavaScript
- Cursor IDE (AI-assisted coding)
- Google Fonts, Coolors.co
- Hostinger (hosting + file manager)
- Chrome DevTools

### Deficiency Trigger
*"Our website looks great, but the data shown is hardcoded in HTML. If a business wants to update their services, we have to manually edit the HTML file every time. There's no way to manage it dynamically. The contact form doesn't actually send emails anywhere — the data goes nowhere. We need a way to make the UI reactive and data-driven."*

---

---

## MODULE 2: Dynamic Frontend — React
### Duration: Weeks 5–8 (4 weeks)

### Real-World Project
**BookEase Frontend v2** — Rebuild the BookEase frontend using React. Add: dynamic service cards loaded from a JSON file, a multi-step booking form with state management, a business dashboard UI with charts, and client-side routing between pages.

*This is the UI a funded startup would build.*

---

### WEEK 5 — Why React Exists + Core Concepts

#### Concepts Covered
- The problem with vanilla JS at scale — why React was invented
- What is a component — the LEGO block mental model
- JSX — HTML inside JavaScript (the syntax that confuses everyone)
- Props — passing data into components
- State (useState) — the core of React reactivity
- Conditional rendering

#### Hands-on Activities
1. Create first React app using Vite (`npm create vite@latest`)
2. **Terminal crash course**: What is npm, what is node_modules, what is package.json
3. Break the BookEase landing page into React components: `<Navbar>`, `<Hero>`, `<Features>`, `<Footer>`
4. Use Cursor: *"Convert this HTML section into a React functional component"*
5. Add a useState toggle to show/hide a mobile menu

---

### WEEK 6 — Lists, Forms & Data Flow

#### Concepts Covered
- Rendering lists with `.map()` — THE most used pattern in React
- Handling form inputs with controlled components
- useEffect — fetching data when a component loads
- Lifting state up — passing data between components
- React folder structure best practices

#### Hands-on Activities
1. Create a `services.json` file with 6 fake services
2. Render service cards dynamically using `.map()` — never hardcode again
3. Build the multi-step booking form with state tracking
4. Build a simple search/filter for services using useState

---

### WEEK 7 — React Router + Styling Systems

#### Concepts Covered
- Client-side routing with React Router v6
- Multiple pages: Home, Services, Book Now, Dashboard
- Tailwind CSS — utility-first styling (the industry standard)
- Component libraries overview: shadcn/ui, Radix UI

#### Hands-on Activities
1. Add React Router — create 4 pages
2. Migrate BookEase styling from vanilla CSS to Tailwind
3. Use Cursor: *"Create a responsive service card component using Tailwind CSS"*
4. Add a navbar with active link highlighting

---

### WEEK 8 — Vibe Coding Sprint + React Polish

#### Concepts Covered
- Recharts / Chart.js for dashboards
- Loading states and error boundaries
- What is a build (`npm run build`) — static files ready for deployment
- Deploying React app to Hostinger (build folder upload)

#### Hands-on Activities
1. **Full Vibe Coding Session**: Use Cursor to generate the entire business dashboard UI with fake chart data. Spend the class reading, understanding, and modifying 10 things about the generated code.
2. Add loading spinners and empty state components
3. Build the final BookEase React app → run `npm run build` → upload `dist/` folder to Hostinger → **React app live on same domain**
4. Update Fiverr/Upwork profile — add "React.js Frontend Development"
5. Update resume — add React, Tailwind, component-based UI

#### Deliverable
**BookEase Frontend v2** — A fully dynamic, multi-page React application deployed to Hostinger. Beautiful service cards, multi-step booking form, business dashboard with charts.

#### Tools & Technologies
- React 18, Vite, React Router v6
- Tailwind CSS, shadcn/ui
- Cursor IDE (heavy use), Claude for component design
- Recharts (dashboard)
- Hostinger deployment

### Deficiency Trigger
*"The booking form is BEAUTIFUL. But when the user clicks Submit — nothing happens. The data goes nowhere. There's no way to see all bookings in a database, no way to send a confirmation email, no way to check if a time slot is already taken. The UI is a car with no engine. We need a backend — a server that receives our data, processes it, and stores it."*

---

---

## MODULE 3: The Backend Brain — Python + FastAPI
### Duration: Weeks 9–12 (4 weeks)

### Real-World Project
**BookEase API** — Build a complete REST API for BookEase: user registration/login, business CRUD, service management, booking creation and management, and email notification trigger. Documented with Swagger UI.

---

### WEEK 9 — Python Fundamentals (Speed Run)

#### Concepts Covered
*Only what's needed to write APIs. No CS theory fluff.*
- Variables, data types, strings, numbers, booleans
- Lists and dictionaries — the two structures you use 90% of the time
- If/else, for loops
- Functions — defining, calling, return values
- Installing Python, pip, virtual environments
- What is a package / library

#### Teaching Note
Students already know logic concepts from JavaScript. Map everything back: *"This is like JS variables, but cleaner."*

#### Hands-on Activities
1. Python in the terminal: 10-minute live drills on variables and functions
2. Build a function that takes a booking dictionary and returns a confirmation message
3. Build a function that filters a list of services by category
4. Use Cursor to generate a Python function → read it → modify 2 things manually

---

### WEEK 10 — FastAPI Fundamentals

#### Concepts Covered
- What is an API — the waiter analogy (client = customer, API = waiter, server = kitchen)
- What is REST — the rules of the road for web APIs
- HTTP methods: GET (read), POST (create), PUT (update), DELETE (remove)
- HTTP status codes: 200, 201, 400, 401, 404, 500
- Installing FastAPI and Uvicorn
- Creating your first route
- Path parameters and query parameters
- Request body with Pydantic models
- Automatic Swagger documentation at `/docs`

#### The Most Important Teaching Moment
Open Swagger UI on a live server and show the class: *"This is where your client can test your API. This is what companies pay backend developers for."*

#### Hands-on Activities
1. Build first FastAPI app — `GET /` returns `{"message": "BookEase API is running"}`
2. Build `GET /services` — returns list of services from a hardcoded list
3. Build `POST /bookings` — receives booking data, prints it, returns confirmation
4. Use Cursor: *"Add a PATCH /bookings/{id} endpoint to update booking status"* → read every line

---

### WEEK 11 — Auth, Middleware & API Design

#### Concepts Covered
- What is authentication vs authorization
- JWT tokens — how login works in modern apps
- Password hashing with bcrypt (never store plain passwords)
- FastAPI dependency injection — the right way to protect routes
- CORS — why the browser blocks your React app from calling your API and how to fix it
- Environment variables (.env files) — never hardcode secrets

#### Hands-on Activities
1. Build `POST /auth/register` — hash password, return user
2. Build `POST /auth/login` — verify password, return JWT token
3. Protect `POST /bookings` — only logged-in users can book
4. Connect React frontend to the FastAPI backend — make `POST /bookings` work from the UI
5. **The CORS moment**: Watch the browser throw a CORS error. Fix it. Understand why it happened.

---

### WEEK 12 — API Integration Sprint

#### Concepts Covered
- Axios in React — making HTTP calls from frontend
- Async/await in JavaScript for API calls
- Error handling on frontend (try/catch, loading states)
- Using environment variables in React (VITE_API_URL)
- API testing with Postman / Swagger

#### Hands-on Activities
1. Connect the React booking form to `POST /bookings` — data now flows from UI to backend
2. Connect the React services list to `GET /services` — pull data from API
3. Implement login flow — React form → POST /auth/login → store JWT → use on protected calls
4. Full integration test: User visits site → sees services → fills booking form → data arrives in API → gets confirmation
5. Update resume and freelance profiles — add "REST API Development, Python, FastAPI"

#### Deliverable
**BookEase API** — Complete REST API with 15+ endpoints, JWT authentication, Swagger documentation. React frontend fully connected to the backend. Runs on localhost.

#### Tools & Technologies
- Python 3.11+, FastAPI, Uvicorn
- Pydantic, python-jose (JWT), passlib (bcrypt)
- Postman, Swagger UI (built-in)
- Axios (in React frontend)
- Cursor IDE (primary coding tool)
- python-dotenv

### Deficiency Trigger
*"The full app works! But the moment I restart the Python server, ALL the bookings are GONE. Data lives only in memory — in a Python list. We have no permanent storage. We need a database — a system that saves our data to disk, allows complex queries, and never loses anything unless we tell it to."*

---

---

## MODULE 4: Persistent Data — PostgreSQL + Full Stack Integration
### Duration: Weeks 13–15 (3 weeks)

### Real-World Project
**BookEase Full Stack (Local)** — Add PostgreSQL to BookEase. All bookings, businesses, users, and services are stored in a real relational database. The entire app runs locally as a production-grade full stack application.

---

### WEEK 13 — Database Fundamentals + PostgreSQL

#### Concepts Covered
- What is a database and why you can't use a text file forever
- Relational databases — tables, rows, columns
- Primary keys and foreign keys — how tables relate to each other
- SQL fundamentals: SELECT, INSERT, UPDATE, DELETE, WHERE, JOIN
- Installing PostgreSQL locally
- pgAdmin — the GUI for PostgreSQL
- Database design for BookEase — drawing the entity relationships
  - Users table, Businesses table, Services table, Bookings table

#### Hands-on Activities
1. Install PostgreSQL + pgAdmin
2. Create the `bookease_db` database
3. Write raw SQL to create the Users, Services, and Bookings tables
4. Insert 5 fake records manually with SQL
5. Write a JOIN query: *"Get all bookings with the service name and business name"*

---

### WEEK 14 — SQLAlchemy + Alembic (ORM + Migrations)

#### Concepts Covered
- What is an ORM — why we don't write raw SQL in FastAPI
- SQLAlchemy models — Python classes that map to database tables
- Creating database sessions and dependencies
- Alembic — database migration tool (version control for your database schema)
- CRUD operations through SQLAlchemy

#### Hands-on Activities
1. Replace all in-memory lists in FastAPI with SQLAlchemy database calls
2. Run first Alembic migration — create tables from Python models
3. Test all endpoints — data now persists between server restarts
4. Use Cursor: *"Convert this raw SQL query into a SQLAlchemy ORM query"*

---

### WEEK 15 — Full Integration + Local Docker

#### Concepts Covered
- What is Docker — the shipping container analogy
- Why Docker matters: *"It works on my machine"* problem solved
- Docker Compose to run React + FastAPI + PostgreSQL together in one command
- Environment variables and secrets management
- Testing the full stack end-to-end

#### Hands-on Activities
1. Write a `docker-compose.yml` for the full BookEase stack
2. Use Cursor to generate the Dockerfile for the FastAPI app
3. Run `docker-compose up` — the entire app starts with one command
4. End-to-end test: Register user → login → see services → book appointment → check booking in database via pgAdmin
5. Update resume: Add "PostgreSQL, Database Design, SQLAlchemy, Docker"

#### Deliverable
**BookEase Full Stack (Local)** — Complete, fully functional application running locally with Docker. Frontend + API + Database all connected. Data persists. Auth works. Swagger docs available.

#### Tools & Technologies
- PostgreSQL 15, pgAdmin
- SQLAlchemy, Alembic
- Docker, Docker Compose
- Python-dotenv, psycopg2

### Deficiency Trigger
*"The app is COMPLETE and works perfectly — on my laptop. But my client is in Mumbai. My laptop would need to be on 24/7 for them to use it. If I close VS Code, the app dies. We need to put this on a real server — a computer on the internet that never turns off. We need cloud deployment."*

---

---

## MODULE 5: Git, GitHub & Version Control
### Duration: Week 16 (1 week — but critical)

### Real-World Project
**BookEase GitHub Repository** — Move the entire BookEase codebase to GitHub with a professional repo structure, README, .gitignore, and branch strategy.

### Why a Standalone Module
Every company uses Git. Every freelance project needs Git. This is non-negotiable career infrastructure.

### Concepts Covered
- What is version control — the "save game" analogy
- What is Git vs GitHub — the tool vs the platform
- Core Git workflow: init → add → commit → push
- Branches — work without breaking the main code
- Pull requests — how teams review code
- .gitignore — what NOT to push (node_modules, .env files, secrets)
- GitHub README — your project's front page

### Hands-on Activities
1. Create GitHub account (if not done)
2. `git init` in BookEase project → first commit
3. Push to GitHub — `bookease` repository is now public
4. Create a `dev` branch → make a change → open a Pull Request → merge to `main`
5. Write a professional README.md for BookEase (use Cursor to generate a draft, then customize)
6. Add GitHub link to Fiverr, Upwork, and resume

### Deliverable
BookEase fully on GitHub. Professional README. Branch workflow understood. This repo becomes the centerpiece of the portfolio.

### Deficiency Trigger
*"The app is on GitHub. But every time we deploy a new version, we have to manually copy files to the server. What if we have 10 clients? There must be a way to auto-deploy every time we push code to GitHub."*

---

---

## MODULE 6: Cloud Deployment — AWS EC2
### Duration: Weeks 17–19 (3 weeks)

### Real-World Project
**BookEase on AWS** — Deploy the complete BookEase stack (React + FastAPI + PostgreSQL) to an AWS EC2 server. The application is live at a public IP with a domain name, HTTPS, and runs 24/7.

---

### WEEK 17 — AWS Fundamentals + EC2 Setup

#### Concepts Covered
- What is cloud computing — renting computers on the internet
- AWS core services overview (only what matters for us):
  - EC2 — virtual servers (this is what we use)
  - S3 — file storage (images, files)
  - RDS — managed database
  - Route 53 — DNS management
  - IAM — who can do what
- AWS Free Tier — what's free and for how long
- What is a VPS vs managed hosting vs serverless
- SSH — how to connect to a remote server from your terminal
- Linux command line basics (only what's needed):
  - `ls`, `cd`, `mkdir`, `pwd`
  - `apt install`, `systemctl`, `nano`
  - File permissions basics

#### Hands-on Activities
1. Create AWS account — configure Free Tier
2. Launch first EC2 instance (Ubuntu 22.04, t2.micro — free tier)
3. Configure Security Groups (open ports 22, 80, 443, 8000)
4. SSH into the server from terminal → students see the server's command line
5. Install Python, Node.js, PostgreSQL, Nginx on the server
6. The "Hello from Server" moment: Run a simple FastAPI app on EC2. Access it from the browser using the EC2 public IP.

---

### WEEK 18 — Deploying BookEase to EC2

#### Concepts Covered
- What is Nginx — the reverse proxy (the traffic director)
- Nginx config — routing `/api` to FastAPI, `/` to React static files
- Process management with `systemd` — keep the app running even after reboot
- Environment variables on Linux server
- Building React for production and serving static files
- SSL certificate with Let's Encrypt (Certbot) — free HTTPS

#### Hands-on Activities
1. Clone the BookEase GitHub repo onto the EC2 server
2. Set up PostgreSQL on the server — create the database and run migrations
3. Start FastAPI with uvicorn + gunicorn, configure as a systemd service
4. Build the React app on the server → serve with Nginx
5. Configure Nginx as a reverse proxy
6. Point the BookEase domain (from Hostinger) to the EC2 IP using DNS A record
7. Install Let's Encrypt SSL → **BookEase is live at https://bookease.yourdomain.com**

---

### WEEK 19 — CI/CD with GitHub Actions

#### Concepts Covered
- What is CI/CD — the automated assembly line for code
- GitHub Actions — automation that runs when you push to GitHub
- The deployment pipeline: push code → tests run → build → deploy to EC2 automatically
- Secrets in GitHub Actions (never hardcode passwords)
- Basic concept of staging vs production environments

#### Hands-on Activities
1. Write a GitHub Actions workflow file (`.github/workflows/deploy.yml`)
2. Use Cursor to generate the workflow → read every step together
3. Push a small change to `main` branch → watch GitHub Actions automatically deploy to EC2
4. The magic moment: *"I changed one word. Pushed to GitHub. 2 minutes later, the live website updated by itself."*
5. Update resume: Add "AWS EC2, Cloud Deployment, CI/CD, Nginx, Linux"
6. Update Upwork/Fiverr: Add "AWS Deployment, Full Stack Deployment"

#### Deliverable
**BookEase LIVE on AWS** — Public URL, HTTPS, auto-deploys on every GitHub push. This is a production-grade deployment. Students can now deploy ANY project for clients.

#### Tools & Technologies
- AWS EC2 (Free Tier), AWS IAM
- Ubuntu 22.04, Nginx, Gunicorn
- Let's Encrypt (Certbot)
- GitHub Actions
- systemd, SSH

### Deficiency Trigger
*"BookEase is live and auto-deploying. But it's a static platform — it does the same thing for every user. The most demanded and highest-paying work right now is AI integration. What if BookEase could answer customer questions, recommend services, automate responses? We need to learn AI application development."*

---

---

## MODULE 7: AI Integration — Building Intelligent Features
### Duration: Weeks 20–21 (2 weeks)

### Real-World Project
**BookEase AI Features** — Add three AI-powered features to BookEase:
1. An AI customer support chatbot that answers questions about services and bookings
2. An AI-powered service recommendation engine (based on user preferences)
3. An automated booking confirmation and follow-up email generator

---

### WEEK 20 — AI Tools Landscape + OpenAI API

#### Concepts Covered
- The AI landscape for developers in 2025:
  - LLMs: ChatGPT/GPT-4o, Claude, Gemini
  - AI APIs vs AI tools vs AI apps
  - What is a prompt, what is a system prompt, what is a token
  - Retrieval-Augmented Generation (RAG) — the concept behind intelligent chatbots
- OpenAI API: how to call it from Python
- Building a simple chatbot with memory (conversation history)
- Streaming responses
- Cost awareness — tokens, pricing, optimization
- LangChain basics — orchestrating AI calls

#### Hands-on Activities
1. Get OpenAI API key → make first API call from Python
2. Build a simple terminal chatbot in 20 lines of Python
3. Build a FastAPI endpoint `POST /ai/chat` that takes a message and returns an AI response
4. Add "system prompt" to make the AI respond as a BookEase assistant
5. Use Cursor: Generate the LangChain-based chat history management → understand it

---

### WEEK 21 — Embedding AI Into the Full Stack

#### Concepts Covered
- Connecting AI endpoints to the React frontend (chat UI)
- Streaming text responses in the browser (Server-Sent Events)
- AI prompt engineering for specific business contexts
- Using Claude API as an alternative to OpenAI
- AI tools for developers:
  - Cursor IDE deep-dive (rules, `.cursorrules` files, project context)
  - GitHub Copilot
  - v0.dev for UI generation
  - Perplexity for research

#### Hands-on Activities
1. Build a chat UI component in React (floating chat widget on BookEase)
2. Connect to `POST /ai/chat` → stream the response word by word
3. Add business context: chatbot knows all services, prices, and policies from the database
4. Build `POST /ai/recommend` — AI recommends services based on user's stated problem
5. Deploy the AI features to EC2 → **BookEase now has a live AI chatbot**
6. **Exploration session**: Browse and demo 10 AI tools together:
   - Cursor, Claude, Midjourney, ElevenLabs, Make.com, Zapier, Perplexity, Notion AI, Gamma.app, Bolt.new

#### Deliverable
**BookEase with AI** — Live web application with an AI chatbot, AI recommendation engine, all deployed on AWS.

#### Tools & Technologies
- OpenAI GPT-4o API, Claude API
- LangChain (Python)
- React chat UI components
- Server-Sent Events (SSE) for streaming
- Cursor IDE (advanced features)

---

---

# 4. MANDATORY TOPICS COVERAGE MAP

| Topic | Module | Week |
|---|---|---|
| HTML fundamentals | Module 1 | Week 2 |
| CSS fundamentals + Flexbox | Module 1 | Week 3 |
| JavaScript fundamentals | Module 1 | Week 4 |
| Vibe coding (Cursor, Claude) | Module 0–1 | Week 1–4 (every session) |
| Responsive UI | Module 1–2 | Week 3–7 |
| React + Tailwind | Module 2 | Week 5–8 |
| Python fundamentals | Module 3 | Week 9 |
| FastAPI + REST APIs | Module 3 | Week 10–11 |
| API integration (frontend ↔ backend) | Module 3 | Week 12 |
| PostgreSQL + SQL | Module 4 | Week 13 |
| SQLAlchemy ORM | Module 4 | Week 14 |
| Docker Compose | Module 4 | Week 15 |
| Git & GitHub | Module 5 | Week 16 |
| AWS EC2 + Linux | Module 6 | Week 17–18 |
| Nginx + SSL | Module 6 | Week 18 |
| CI/CD (GitHub Actions) | Module 6 | Week 19 |
| AI APIs + Chatbot | Module 7 | Week 20–21 |
| Domain, DNS, Hosting | Module 1 | Week 4 |
| Debugging & problem-solving | All modules | Every week |
| Product thinking | All modules | Weekly reflection |
| System design basics | Module 4 | Week 15 |

---

---

# 5. CAPSTONE PROJECT

## Duration: Weeks 22–23

### Project: *HireLocal* — AI-Powered Local Talent Marketplace

**What it is**: A platform where freelancers and skilled local workers (plumbers, electricians, tutors, designers, developers) can create profiles and list services, and clients can search, compare, and hire — with an AI assistant to help match needs to providers.

**Why this project?**
- More complex than BookEase → proves growth
- Real business model (can be monetized)
- Every skill from every module is used
- Portfolio-defining project

### Tech Stack
| Layer | Technology |
|---|---|
| Frontend | React 18 + Tailwind + shadcn/ui |
| Backend | FastAPI + Python |
| Database | PostgreSQL + SQLAlchemy |
| AI Feature | OpenAI API — AI matchmaking chatbot |
| Auth | JWT (FastAPI) |
| Deployment | AWS EC2 + Nginx + GitHub Actions |
| Storage | AWS S3 (profile pictures, portfolio files) |
| Domain | Custom domain with HTTPS |

### Features Built During Capstone
1. **Freelancer onboarding**: Register, create profile, add skills, upload portfolio
2. **Client search**: Search by skill, location, price range, rating
3. **AI Matchmaking Chat**: *"I need someone to fix my plumbing in Pune under ₹500"* → AI returns 3 best matches
4. **Booking & Messaging**: Hire a freelancer → messaging thread → booking confirmation
5. **Review System**: After job completion, rate and review
6. **Admin Dashboard**: Business metrics, user management
7. **Payment Integration Concept**: Razorpay/Stripe integration walkthrough (conceptual + setup)

### Week 22 — Build Sprint
Students build assigned features in parallel. Daily stand-ups. Teacher reviews pull requests. Code review sessions as a group.

### Week 23 — Polish, Deploy, Present
- Final bug fixes and UI polish
- Deploy to EC2 with custom domain
- Record a 3-minute demo video
- **Demo Day**: Each student presents their version live in class
- Peer feedback session

### Deliverable
A live, deployed, portfolio-ready full stack AI-powered web application. Live URL. GitHub repository. Demo video.

---

---

# 6. FREELANCING & CAREER MODULE

## Duration: Week 24 (Final Week)

### Session 1: Resume & Portfolio (2 hours)

#### Resume Building
- What hiring managers look for in 2025 (and what they ignore)
- The 1-page rule for freshers
- Using AI to write your resume (ChatGPT prompt: *"Write a resume for a junior full stack developer with these projects and skills..."*)
- Skills section: React, Python, FastAPI, PostgreSQL, AWS, Docker, Git, AI APIs
- Projects section: BookEase (with live URL + GitHub) + HireLocal (with live URL + GitHub)
- What NOT to put on a resume

#### Portfolio Setup
- GitHub profile optimization: profile README, pinned repos, contribution graph
- Write a professional README for both projects (Cursor can help)
- Record Loom video walkthrough of both projects (5 minutes each)
- Host both projects on AWS with custom subdomains

---

### Session 2: Freelancing Platform Setup (2 hours)

#### Fiverr
- Gig creation: "I will build you a professional business website"
- Gig creation: "I will build you a React frontend with Tailwind CSS"
- Gig creation: "I will create a REST API with Python and FastAPI"
- Gig creation: "I will add an AI chatbot to your website"
- Pricing strategy: Start at ₹2,000–5,000, build reviews, scale to ₹20,000+
- Gig image design (Canva template)

#### Upwork
- Profile setup — headline, bio, hourly rate
- Writing your first proposal (AI-assisted draft, then personalize)
- How to get first 5-star review (discount for first client, overdeliver)
- Building a JSS (Job Success Score)

#### LinkedIn
- Optimizing profile for developer roles
- Posting about your projects (the right way)
- Connecting with recruiters and hiring managers
- The "build in public" strategy

---

### Session 3: Getting Your First Client / Job (2 hours)

#### Job Track
- Where to apply: LinkedIn, Naukri, Internshala, AngelList/Wellfound
- How to crack a technical interview with AI-assisted preparation
- Common interview questions for junior developers
- How to negotiate salary
- What to expect in the first 90 days at a company

#### Freelance Track
- Warm outreach: WhatsApp message template for local businesses
- Cold outreach: LinkedIn message template
- Discovery call structure: *"Tell me about your business, what problem do you want to solve?"*
- Proposal writing template
- Contract basics (use a simple one-page contract)
- Milestone-based payment structure
- Managing client expectations (the #1 skill no one teaches)

#### Pricing Guide
| Service | Beginner Price | 6-Month Price |
|---|---|---|
| Business landing page | ₹5,000–15,000 | ₹20,000–40,000 |
| React frontend | ₹10,000–25,000 | ₹30,000–60,000 |
| Full stack web app | ₹25,000–60,000 | ₹75,000–1,50,000 |
| AI chatbot integration | ₹15,000–30,000 | ₹40,000–80,000 |
| Monthly maintenance | ₹3,000–8,000/mo | ₹10,000–25,000/mo |

---

### Session 4: Personal Branding (2 hours)

- Why developers who write online earn 3× more than those who don't
- Starting a LinkedIn newsletter or Twitter/X thread series
- Sharing your projects — what to write, when to write
- Building your niche: *"The developer who builds AI-powered booking systems for local businesses"*
- YouTube/Instagram Reels: recording short dev tips
- The compound effect: consistency over virality

---

---

# 7. ENTREPRENEUR TRACK

### Woven Throughout the Course (Not a Separate Module)

At the end of every module, there is a 30-minute **"Entrepreneur Lens"** session:

| After Module | Entrepreneur Lens Topic |
|---|---|
| Module 1 | "How to find clients for website development in your city" |
| Module 2 | "How to position a React app as a premium service vs a regular website" |
| Module 3 | "What is a SaaS? How does charging per API call work?" |
| Module 4 | "How does a database design decision affect your product's scalability?" |
| Module 5 | "How open source and GitHub visibility can bring clients to you" |
| Module 6 | "Cloud costs and pricing — how to price hosting into client contracts" |
| Module 7 | "How to productize an AI chatbot as a monthly SaaS" |

### Converting a Project into a Product (Week 24 — Day 3)

1. **Validate before you build**: Reddit, WhatsApp groups, cold calls — test the idea with 10 real people before writing code
2. **MVP thinking**: What is the absolute minimum version that solves the core problem?
3. **Finding the pain**: The founder's job is to find problems, not solutions
4. **BookEase as a SaaS**: How to charge salons ₹999/month for BookEase → ₹1 lakh/year at 100 customers
5. **HireLocal as a marketplace**: Commission model, freemium model, premium listings
6. **Launch checklist**: Landing page → waitlist → 10 beta users → iterate → paid plan
7. **Tools for solo founders**: Razorpay, Notion, WhatsApp Business API, Zapier, Make.com

---

---

# 8. WEEK-BY-WEEK BREAKDOWN

| Week | Module | Main Topic | Deliverable |
|---|---|---|---|
| **1** | Module 0 | Orientation — how the internet works, AI tools setup | Environment setup, first AI-assisted code |
| **2** | Module 1 | HTML fundamentals | BookEase HTML skeleton |
| **3** | Module 1 | CSS fundamentals + Flexbox | Styled BookEase landing page |
| **4** | Module 1 | JavaScript basics + Domain/DNS + Deployment | **BookEase live on Hostinger** ✅ |
| **5** | Module 2 | Why React, Components, JSX, State | First React app running locally |
| **6** | Module 2 | Lists with `.map()`, Forms, Data Flow | Dynamic service cards from JSON |
| **7** | Module 2 | React Router, Tailwind CSS | Multi-page BookEase React app |
| **8** | Module 2 | Vibe Coding sprint, Build + Deploy | **BookEase React app live on Hostinger** ✅ |
| **9** | Module 3 | Python fundamentals (speed run) | Python CRUD functions |
| **10** | Module 3 | FastAPI — routes, methods, Pydantic | First API with Swagger docs |
| **11** | Module 3 | JWT Auth, CORS, protected routes | Auth system complete |
| **12** | Module 3 | React ↔ FastAPI integration | **Full frontend-backend integration** ✅ |
| **13** | Module 4 | PostgreSQL, SQL, database design | BookEase schema in pgAdmin |
| **14** | Module 4 | SQLAlchemy ORM, Alembic migrations | Data persists to database |
| **15** | Module 4 | Docker Compose, full local stack | **Full local stack running in Docker** ✅ |
| **16** | Module 5 | Git, GitHub, branches, PRs | **BookEase on GitHub** ✅ |
| **17** | Module 6 | AWS fundamentals, EC2 setup, Linux | EC2 server running in AWS |
| **18** | Module 6 | Nginx, SSL, domain connection | **BookEase on AWS with HTTPS** ✅ |
| **19** | Module 6 | GitHub Actions, CI/CD pipeline | **Auto-deployment pipeline live** ✅ |
| **20** | Module 7 | OpenAI API, chatbot fundamentals | AI chatbot in terminal + FastAPI endpoint |
| **21** | Module 7 | AI in full stack, AI tools exploration | **BookEase AI chatbot live on AWS** ✅ |
| **22** | Capstone | HireLocal — build sprint | 80% of capstone built |
| **23** | Capstone | Polish, deploy, Demo Day | **HireLocal LIVE on AWS** ✅ |
| **24** | Career | Resume, freelance profiles, client strategy | Resume + Fiverr/Upwork gigs live |

---

---

# 9. TEACHING STRATEGY

## 9.1 The 3-Part Session Structure (Every 2-Hour Class)

| Time | Activity | Purpose |
|---|---|---|
| 0:00–0:20 | **Concept** — Teacher explains the "why" with a real-world analogy | Build mental model before any code |
| 0:20–1:20 | **Live Build** — Teacher codes, students follow on their own machine | Kinesthetic learning — typing it yourself matters |
| 1:20–1:50 | **Solo Sprint** — Students modify or extend what was just built | Catch gaps immediately while teacher circulates |
| 1:50–2:00 | **Reflection** — What did we build? What can't we do yet? (Deficiency Trigger) | Set up motivation for next session |

---

## 9.2 When to Use AI Tools vs Manual Coding

### Manual Coding (Teacher codes first, no AI)
- First introduction of any concept
- Core logic: loops, functions, state management
- Debugging sessions
- SQL queries
- API route design

**Why**: Students must build the mental model before outsourcing the typing.

### AI-Assisted (Cursor/Claude in action)
- Boilerplate (setting up a new project structure)
- Repeating a pattern learned manually (after doing it once by hand)
- CSS styling of complex components
- Generating test data / mock data
- Documentation and README writing
- Refactoring after understanding

**Rule to teach students**: *"Use AI to go faster, not to go without understanding. If you can't read, explain, and edit any line of AI-generated code, you don't own it — the AI owns it."*

---

## 9.3 The "I Can't, AI Can" Exercise

Every module should have at least one moment where:
1. The teacher shows a hard problem
2. The class tries to solve it manually (struggles)
3. They ask Cursor/Claude to solve it
4. THEN — they spend 20 minutes reading and understanding the AI output
5. They intentionally break one thing and fix it manually

This teaches empowerment, not dependency.

---

## 9.4 Preventing Common Teaching Mistakes

| Mistake | Prevention |
|---|---|
| Moving too fast | Check understanding with "explain it back to me" exercise — 1 student explains the concept in plain Hindi/English |
| Copy-paste culture | Require students to type everything, even AI output. Typing forces reading. |
| Theory overload | If you can't show it working in 5 minutes, skip the theory. Teach it when it's needed. |
| Students getting stuck silently | WhatsApp group + designated "buddy pairs" for peer support |
| Skipping debugging | Intentionally introduce bugs in live code and debug them together. Debugging is a skill. |
| AI dependency | Monthly "No AI Week" — one project per month must be 50% manually coded |

---

## 9.5 Assessment Structure

| Type | Frequency | Weight |
|---|---|---|
| Weekly mini-project | Every week | "Did they build it?" check |
| Module deliverable | Every 3–4 weeks | Deployed project review |
| Peer code review | Bi-weekly | Reading others' code |
| Demo Day | Week 23 | Capstone presentation |
| Portfolio audit | Week 24 | Resume + profiles live |

---

## 9.6 Handling Diverse Paces

- **Slower students**: Assign a "buddy" (faster student) for pair programming
- **Faster students**: Extension challenges — *"Now add pagination to that API"* or *"Add a dark mode toggle"*
- **Stuck moments**: Teacher policy: if more than 3 students are stuck on the same thing, stop and reteach the concept
- **The 10-minute rule**: Student tries for 10 minutes alone, then asks their buddy, then asks the class group, then asks the teacher. Builds problem-solving muscle.

---

## 9.7 Building a Community (Compounding Effect)

- **WhatsApp group**: Share every deployed project link here — social proof and celebration
- **"What I Built Today" message**: Students post one sentence + screenshot every session
- **Alumni network**: Students who finish become mentors for the next batch
- **Monthly industry guest talk**: Invite a working developer, freelancer, or founder for a 30-minute live Q&A

---

---

# 10. TOOLS MASTER LIST

## Development Tools
| Tool | Use |
|---|---|
| Cursor IDE | Primary coding tool — AI-assisted development |
| VS Code | Backup editor, extensions ecosystem |
| Chrome DevTools | Debugging frontend |
| Postman | API testing |
| pgAdmin | PostgreSQL GUI |
| Docker Desktop | Local containerization |

## AI Tools
| Tool | Use |
|---|---|
| Claude (Anthropic) | Complex code generation, code review |
| ChatGPT (OpenAI) | Concepts, documentation, proposals |
| GitHub Copilot | In-editor autocomplete |
| v0.dev | React component generation |
| Bolt.new | Full app scaffolding |
| Perplexity | Technical research |

## Deployment & Cloud
| Tool | Use |
|---|---|
| Hostinger | Shared hosting, domain management |
| AWS EC2 | Production server |
| AWS S3 | File storage |
| GitHub Actions | CI/CD automation |
| Nginx | Reverse proxy |
| Let's Encrypt | Free SSL certificates |

## Freelancing & Career
| Platform | Use |
|---|---|
| GitHub | Code portfolio |
| Fiverr | Entry-level freelance projects |
| Upwork | Higher-value freelance projects |
| LinkedIn | Professional network + job search |
| Naukri / Internshala | Indian job market |
| Canva | Gig images, presentations |

---

---

# 11. WHAT STUDENTS CAN CLAIM AFTER THE COURSE

## Skills on Resume
```
Frontend: HTML5, CSS3, JavaScript (ES6+), React 18, Tailwind CSS
Backend: Python 3.11, FastAPI, REST API Design, JWT Authentication
Database: PostgreSQL, SQLAlchemy ORM, SQL
DevOps: Docker, AWS EC2, Nginx, CI/CD (GitHub Actions)
AI: OpenAI API, Claude API, LangChain, AI-assisted development (Cursor)
Tools: Git, GitHub, Postman, pgAdmin, Linux (Ubuntu)
Concepts: Responsive Design, System Design Basics, API Integration
```

## Projects on Portfolio
1. **BookEase** — Live booking platform (AWS, React + FastAPI + PostgreSQL + AI chatbot)
2. **HireLocal** — Live freelance marketplace (AWS, full stack + AI matching)
3. **Personal Website** — Live on Hostinger with custom domain

## Job Roles Accessible
- Junior Frontend Developer
- Junior Full Stack Developer
- Junior Backend Developer (Python)
- React Developer
- API Developer

## Freelance Services Sellable from Day 1
- Business websites (₹10K–40K)
- React web apps (₹25K–80K)
- Full stack platforms (₹50K–1.5L)
- AI chatbot integration (₹20K–60K)
- Cloud deployment setup (₹15K–40K)

---

*End of Curriculum — BookEase to HireLocal, Zero to Self-Reliant.*
