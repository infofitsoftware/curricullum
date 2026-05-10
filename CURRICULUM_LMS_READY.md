# LMS Curriculum Structure (Topic → Lessons → Project)
## Program: Modern Software Engineer (Beginner to Job/Freelance/Startup)
## Duration: 24 Weeks (6 Months)

Use this file directly for LMS module creation.  
Each topic is intentionally short so students feel consistent progress.

---

## Topic 0: Program Kickoff & Setup
**Duration:** Week 1  
**Outcome:** Students are ready to code and use AI tools correctly.

### Lessons
1. Different types of computer applications (website, web app, mobile app, desktop app, SaaS)
2. What is coding vs what is programming (difference with real examples)
3. How the web works (browser, server, domain, DNS)
4. Files, folders, terminal, localhost, ports
5. VS Code/Cursor setup
6. GitHub account setup
7. Vibe coding basics (how to use Cursor/Claude/ChatGPT responsibly)
8. Prompt engineering basics (clear prompts, context, constraints, output format)
9. Manual coding vs AI-assisted coding rules
10. Course roadmap: BookEase project spine and 6-month journey

### Topic Project
- **Project:** “My First Web Page”
- **Deliverable:** One simple page built manually, then improved with AI assistance

---

## Topic 1: HTML Fundamentals
**Duration:** Week 2  
**Outcome:** Students can build and explain a semantic multi-section HTML page manually, then improve it with AI using clear prompts and verification.

### Lessons
1. From Topic 0 to Topic 1: converting the BookEase idea into page sections (Hero, Features, Testimonials, CTA, Footer)
2. HTML tags, elements, attributes
3. Document structure (`<!DOCTYPE>`, `html`, `head`, `body`)
4. Semantic HTML
5. Links, images, lists, tables
6. Forms and input elements
7. Page structure for business websites
8. AI-assisted HTML workflow: prompt -> generate -> verify -> manual fixes

### Topic Project
- **Project:** BookEase Landing Page Skeleton
- **Deliverable:** Structured multi-section HTML page with:
  - Manual first draft and AI-improved version
  - Semantic sections (`header`, `main`, `section`, `footer`)
  - GitHub commit history (meaningful commit messages)
  - Short reflection: what AI improved and what was fixed manually

---

## Topic 2: CSS & Responsive Design
**Duration:** Week 3  
**Outcome:** Students can style the Topic 1 HTML skeleton into a clean, responsive landing page and validate design decisions with AI support.

### Lessons
1. From Topic 1 to Topic 2: freezing HTML structure before styling
2. CSS selectors and box model
3. Typography, colors, spacing
4. Flexbox essentials
5. Responsive design with media queries
6. Mobile-first layout checks
7. AI-assisted styling workflow: generate CSS options -> compare -> keep best -> manual polish

### Topic Project
- **Project:** Styled BookEase Landing Page
- **Deliverable:** Responsive design that works on phone/tablet/desktop with:
  - Consistent typography, spacing, and color system
  - Mobile-first CSS and breakpoint checks
  - Before/after comparison of at least one AI styling suggestion
  - GitHub commit history with meaningful commit messages

---

## Topic 3: JavaScript Basics + First Deployment
**Duration:** Week 4  
**Outcome:** Students can add core JavaScript interactivity to the styled BookEase page, debug common issues, and deploy a working live version.

### Lessons
1. From Topic 2 to Topic 3: keeping HTML/CSS stable while adding JS behavior
2. Variables, data types, conditions, loops
3. Functions and basic logic
4. DOM manipulation
5. Events and form validation
6. Debugging basics (console, common runtime errors, fixing AI-generated JS mistakes)
7. Hosting basics (domain, DNS, SSL)
8. Deploying on Hostinger
9. AI-assisted JavaScript workflow: prompt -> test in browser -> debug -> refine

### Topic Project
- **Project:** Interactive BookEase Landing Site
- **Deliverable:** Live website URL on hosting with:
  - At least 3 JavaScript interactions (for example: menu toggle, form validation, dynamic section update)
  - No blocking console errors in browser
  - One bug-fix log showing issue -> diagnosis -> final fix
  - GitHub commit history with meaningful commit messages

---

## Topic 4: Stabilization Sprint 1 (Client-Style Build)
**Duration:** Week 5  
**Outcome:** Students can independently deliver a client-style responsive website from brief to deployment with clear planning, execution, and QA.

### Lessons
1. From Topic 3 to Topic 4: applying first deployment experience to a new client brief
2. Requirement breakdown from a client brief
3. Planning sections and UI blocks
4. Rebuilding faster with clean HTML/CSS/JS
5. AI-assisted execution: generating alternatives, validating output, and keeping code quality
6. Mobile QA and final polish
7. Handoff basics: preparing project notes for client/team review

### Topic Project
- **Project:** Choose one: Gym/Cafe/Salon/Portfolio website
- **Deliverable:** Fully responsive, deployed client-style website with:
  - Brief-to-build plan (sections, features, timeline)
  - Live deployed URL and GitHub repository link
  - QA checklist evidence (mobile, tablet, desktop, form behavior, broken links)
  - Short delivery note: scope completed, limitations, and next improvements

---

## Topic 5: React Foundations
**Duration:** Week 6  
**Outcome:** Students can convert a static client-style page into a React component-based application with reusable UI and state-driven behavior.

### Lessons
1. From Topic 4 to Topic 5: moving from static pages to component architecture
2. Why React and component thinking
3. JSX fundamentals
4. Props and reusable components
5. State with `useState`
6. Event handling in React
7. Basic project structure and file organization in React apps
8. AI-assisted React workflow: scaffold -> review component boundaries -> refine manually

### Topic Project
- **Project:** BookEase Frontend v1 in React
- **Deliverable:** Componentized homepage and service cards with:
  - Clear component tree (for example: Header, Hero, Services, Testimonials, Footer)
  - Reusable card/list component driven by props
  - At least one state-based interaction using `useState`
  - GitHub commit history with meaningful commit messages

---

## Topic 6: React Data Flow & Routing
**Duration:** Week 7  
**Outcome:** Students can build a multi-page React app with routing, data-driven UI, and reliable loading/error handling.

### Lessons
1. From Topic 5 to Topic 6: extending component-based UI into multi-page user journeys
2. Lists with `.map()`
3. Controlled forms
4. `useEffect` basics
5. React Router fundamentals
6. Basic loading and error states
7. Shared layout and navigation patterns across pages
8. AI-assisted debugging for data flow and routing issues

### Topic Project
- **Project:** BookEase Multi-Page Frontend
- **Deliverable:** Home/Services/Book pages with dynamic data and:
  - Working navigation between routes
  - At least one form with controlled inputs and validation feedback
  - Clear loading and error state handling on one data-driven section
  - GitHub commit history with meaningful commit messages

---

## Topic 7: TypeScript for React
**Duration:** Week 8  
**Outcome:** Students can add practical TypeScript types to a React app to reduce runtime bugs and improve code reliability.

### Lessons
1. From Topic 6 to Topic 7: converting existing React flows into type-safe code
2. TypeScript basics (`string`, `number`, `boolean`, arrays)
3. Interfaces and type aliases
4. Props typing in components
5. Typed state and typed API responses
6. Common TS errors and fixes
7. Gradual migration strategy (`.jsx`/`.js` to `.tsx`/`.ts`) without breaking features
8. AI-assisted TypeScript workflow: generate types -> validate compiler errors -> refine manually

### Topic Project
- **Project:** Type-safe BookEase Frontend
- **Deliverable:** React app migrated to TypeScript basics with:
  - Typed component props for core UI components
  - Typed state for key interactive features
  - Typed API response model for at least one data flow
  - Resolved TypeScript compiler errors and clean commit history

---

## Topic 8: Stabilization Sprint 2 (No-AI Week)
**Duration:** Week 9  
**Outcome:** Students can build and debug a small React+TypeScript app independently without AI assistance, proving true skill retention.

### Lessons
1. From Topic 7 to Topic 8: validating TypeScript and React skills without AI assistance
2. Planning without AI
3. Manual component building
4. Manual debugging workflow
5. Code review and self-assessment
6. Time-boxed implementation strategy for interview-style coding tasks
7. Post-sprint reflection: what to automate later with AI vs what must stay manual

### Topic Project
- **Project:** Mini Booking App (No AI)
- **Deliverable:** Working React+TS mini app built manually with:
  - At least 3 reusable components and one typed form flow
  - Clean TypeScript compile and no blocking runtime errors
  - Self-review checklist (code quality, naming, structure, edge cases)
  - Sprint note documenting challenges, fixes, and confidence level

---

## Topic 9: Python Fundamentals for Backend
**Duration:** Week 10  
**Outcome:** Students can write clean Python backend logic, structure code into reusable modules, and prepare for API development in upcoming topics.

### Lessons
1. From Topic 8 to Topic 9: moving from frontend logic mindset to backend problem solving
2. Python syntax and data types
3. Lists/dictionaries
4. Conditions/loops/functions
5. Basic data transformation logic
6. Virtual environment and package installation
7. Functions, modules, and file organization for backend projects
8. Error handling basics (`try`/`except`) and input validation
9. Reading/writing JSON files and simple API-like data handling
10. AI-assisted Python workflow: generate logic -> run tests/checks -> debug -> refine manually

### Topic Project
- **Project:** Booking Logic Scripts in Python
- **Deliverable:** Python scripts for filtering/searching/price logic with:
  - Modular function-based structure (not one long script)
  - Input validation and basic error handling
  - JSON-based input/output simulation for booking data
  - GitHub commit history with meaningful commit messages

---

## Topic 10: FastAPI Basics
**Duration:** Week 11  
**Outcome:** Students can build and test a structured FastAPI REST API with validated input/output models and reliable error handling.

### Lessons
1. From Topic 9 to Topic 10: converting Python business logic into API endpoints
2. API and HTTP method basics
3. FastAPI setup and route creation
4. Request/response models with Pydantic
5. Path/query params
6. Status codes, validation errors, and exception handling
7. Swagger API documentation
8. API testing basics with Postman/Swagger and response verification
9. AI-assisted backend workflow: generate endpoint draft -> test responses -> fix edge cases manually

### Topic Project
- **Project:** BookEase API v1
- **Deliverable:** CRUD endpoints for services/bookings with:
  - Input/output validation using Pydantic models
  - Proper status codes and clear error responses
  - Tested endpoint collection (Postman or Swagger test evidence)
  - GitHub commit history with meaningful commit messages

---

## Topic 11: Auth, Security Basics, Integration
**Duration:** Week 12  
**Outcome:** Students can implement secure authentication, protect backend/frontend routes, and integrate React with FastAPI using production-style practices.

### Lessons
1. From Topic 10 to Topic 11: adding identity and access control to existing APIs
2. JWT auth basics
3. Password hashing
4. Protected routes
5. CORS and `.env` basics
6. Token storage strategy and logout/session handling
7. React to API integration (Axios/fetch)
8. Auth error handling (401/403), route guards, and user feedback states
9. AI-assisted security workflow: generate auth scaffold -> verify security checklist -> patch gaps manually

### Topic Project
- **Project:** Auth-Enabled BookEase
- **Deliverable:** Login + protected booking flow with:
  - Register/login/logout flow and hashed passwords
  - JWT-based protected backend endpoints and frontend route guards
  - Environment-based secret/config management (`.env`)
  - Security and integration test evidence (invalid token, expired token, unauthorized access)

---

## Topic 12: Stabilization Sprint 3 (Backend Reinforcement)
**Duration:** Week 13  
**Outcome:** Students can design, build, and verify a FastAPI service independently, applying patterns from Topics 10–11 (validation, errors, auth awareness) without step-by-step hand-holding.

### Lessons
1. From Topic 11 to Topic 12: carrying auth, validation, and integration discipline into a new API domain (inventory/orders)
2. API design checklist (resources, naming, HTTP verbs, status codes)
3. Validation and error handling (Pydantic, consistent error bodies)
4. Testing endpoints in Swagger/Postman (happy path + failure cases)
5. Refactor and cleanup (routers, dependencies, file layout)
6. Documentation quality (`README`, Swagger as contract, optional OpenAPI notes)
7. Time-boxed rebuild: plan -> implement -> test -> tighten

### Topic Project
- **Project:** Mini Inventory/Orders API
- **Deliverable:** Independent API with clean endpoints and:
  - CRUD or core workflows for inventory/items and orders (or equivalent domain)
  - Validated models and predictable error responses
  - Test evidence (Swagger/Postman screenshots or exported collection)
  - `README` with run instructions and API overview
  - GitHub commit history with meaningful commit messages

---

## Topic 13: PostgreSQL & SQL
**Duration:** Week 14  
**Outcome:** Students can model relational data in PostgreSQL, write correct SQL for reads and writes, and justify schema choices for a booking-style product.

### Lessons
1. From Topic 12 to Topic 13: why APIs need durable storage and how tables map to resources
2. Tables, rows, primary/foreign keys, constraints, and indexes (basics)
3. Basic SQL queries (`SELECT`, `INSERT`, `UPDATE`, `DELETE`)
4. Joins and filtering (`INNER`/`LEFT`, `WHERE`, `ORDER BY`, `LIMIT`)
5. Aggregates and grouping (`COUNT`, `SUM`, `AVG`, `MIN`/`MAX`, `GROUP BY`, `HAVING`)
6. Database schema design for BookEase (entities, relationships, normalization trade-offs)
7. Transactions and isolation (conceptual: when to commit, avoid partial updates)
8. AI-assisted SQL workflow: draft queries -> run against real data -> fix errors and edge cases manually

### Topic Project
- **Project:** BookEase Database Setup
- **Deliverable:** DB schema + sample data + key queries with:
  - `CREATE TABLE` scripts or migration-style SQL files in the repo
  - Seed data that exercises foreign keys and realistic booking scenarios
  - Documented queries for common product needs (list services, bookings by user/date, availability checks)
  - At least two aggregate reports (for example: bookings per day/week, revenue or count per service) using `GROUP BY`/`HAVING` where appropriate
  - Short design note: tables, keys, and why relationships are modeled this way

---

## Topic 14: ORM + Migrations + Full Stack Persistence
**Duration:** Week 15  
**Outcome:** Students can map the Topic 13 schema to SQLAlchemy models, evolve the database safely with Alembic migrations, and run a FastAPI backend that reads and writes Postgres end to end.

### Lessons
1. From Topic 13 to Topic 14: from hand-written SQL/schema files to ORM models and repeatable migrations
2. SQLAlchemy models (columns, types, relationships, constraints)
3. Alembic migrations (create, upgrade, downgrade awareness, migration review before apply)
4. DB session patterns for FastAPI (session per request, dependency injection, commit/rollback)
5. Replace in-memory or fake storage with Postgres-backed repositories/services
6. Query patterns with the ORM (filters, joins, avoiding N+1 basics)
7. AI-assisted persistence workflow: scaffold models/migrations -> review for correctness -> test against real DB

### Topic Project
- **Project:** Persistent BookEase API
- **Deliverable:** Fully DB-backed backend with:
  - Alembic migration history that matches the intended BookEase schema
  - CRUD or core flows hitting Postgres (no production-critical data left in memory only)
  - Evidence of safe schema change (at least one follow-up migration after the initial create)
  - Short runbook: how to apply migrations and reset local data when needed
  - GitHub commit history with meaningful commit messages

---

## Topic 15: Docker + Local Full Stack Run
**Duration:** Week 16  
**Outcome:** Students can run the Topic 14–15 stack (API + Postgres + optional frontend) locally in containers with repeatable commands, sane env configuration, and basic troubleshooting.

### Lessons
1. From Topic 14 to Topic 15: from "works on my machine" to a reproducible local environment the whole team can share
2. Docker basics (images, containers, ports, volumes, logs)
3. Dockerfile fundamentals (base image, layers, `CMD`/`ENTRYPOINT`, build context)
4. Docker Compose for app + DB (services, networks, named volumes, depends_on / healthchecks)
5. Environment config for containers (`.env` for local dev, secrets not baked into images)
6. Daily workflow: build, up/down, view logs, exec into a container for debugging
7. AI-assisted Docker workflow: generate Compose/Dockerfile drafts -> security review (no secrets in repo) -> test locally and fix manually

### Topic Project
- **Project:** Containerized BookEase
- **Deliverable:** One-command local startup with:
  - `docker compose` (or documented equivalent) bringing up API + database (and frontend if already in scope)
  - Persistent DB data via volumes and documented reset steps
  - `README` section: prerequisites, env variables, URLs/ports, common fixes (port in use, migration order)
  - Evidence of a clean run (screenshot or short screen recording optional; or pasted log snippet)

---

## Topic 16: Git, GitHub, Team Workflow
**Duration:** Week 17  
**Outcome:** Students can collaborate using Git and GitHub like a product team: branches, pull requests, constructive review, and traceability from idea to merged code.

### Lessons
1. From Topic 15 to Topic 16: sharing the same runnable project via Git so teammates can clone and follow the Docker/README setup
2. Git core commands (status, diff, add, commit, push, pull, fetch, stash basics)
3. Branching strategy (feature branches, protected `main`, meaningful branch names)
4. Pull requests and review flow (description, scope, linking issues, addressing feedback)
5. Merge conflicts: causes, resolution, and prevention with small PRs
6. Agile basics (tickets, standups, sprints) mapped to how work lands in GitHub (issues → branch → PR → merge)
7. Professional README writing (setup, env, how to run with Docker, contribution expectations)
8. AI-assisted Git hygiene: draft commit messages and PR text -> verify diffs and authorship yourself

### Topic Project
- **Project:** Team Workflow Simulation
- **Deliverable:** PR-based feature merge with code review and:
  - Feature branch off `main`, multiple commits with clear messages
  - PR description (what/why, test notes, screenshots if UI)
  - At least one round of review feedback addressed (or documented reviewer checklist)
  - Merged outcome or equivalent documented approval state suitable for your LMS

---

## Topic 17: Testing Basics
**Duration:** Week 18  
**Outcome:** Students can define test cases, automate API checks, run focused automated tests, and report defects so a teammate can reproduce and fix them.

### Lessons
1. From Topic 16 to Topic 17: tests and bug reports turn collaboration and review into confidence before merge and deploy
2. Testing mindset for beginners (risk-based testing: what must never break vs nice-to-have)
3. API test cases in Postman (happy path, validation errors, auth failures, edge cases)
4. Pytest basics for FastAPI (`TestClient`, fixtures, organizing `tests/`, running the suite locally)
5. Frontend testing awareness (React Testing Library intro: render, user events, one meaningful component test)
6. Bug report writing (steps to reproduce, expected vs actual, environment, logs, severity)
7. AI-assisted testing workflow: generate test ideas and draft tests -> run and fix failures -> keep tests small and trustworthy

### Topic Project
- **Project:** BookEase Test Pack
- **Deliverable:** Test checklist + Postman collection + basic pytest file with:
  - Manual QA checklist covering critical user/API paths (aligned with BookEase scope)
  - Importable Postman collection with folders for main flows and error cases
  - At least one pytest module exercising FastAPI routes (including one negative case, for example 401/422)
  - One short bug-report example filled with a realistic defect (real or simulated)
  - GitHub commit history with meaningful commit messages

---

## Topic 18: AWS EC2 Deployment (Deep Learning)
**Duration:** Week 19  
**Outcome:** Students can provision EC2 correctly and recognize where other core AWS services fit (networking, storage, databases, observability, secrets, DNS) so later topics and real jobs make sense—not EC2 in isolation.

### Lessons
1. From Topic 17 to Topic 18: deploy only what you can verify; smoke checks mirror Postman/pytest flows
2. AWS core concepts (regions, AZs, billing awareness, EC2, IAM users/roles, key pairs, security groups as a firewall)
3. VPC essentials at a useful level (VPC, subnets, route tables, internet gateway; why instances live in a network context)
4. Linux server basics + SSH (permissions, logs, processes)
5. Server setup for app runtime (dependencies, environment variables on the server, no secrets committed to Git)
6. Running the app under a resilient pattern (for example `systemd` service or documented process manager) and restart-on-failure basics
7. Production config basics (`DEBUG=false`, CORS, DB URL from env, health check endpoint)
8. Amazon S3 (buckets, object policies vs IAM, common uses: uploads/backups/artifacts)
9. Amazon RDS (managed Postgres/MySQL vs running Postgres on the same EC2; security groups to the DB; when to migrate)
10. Observability with CloudWatch (log groups, metrics, alarms; tying app/system logs to one place)
11. Secrets: AWS Secrets Manager or Systems Manager Parameter Store vs pasting secrets over SSH (rotation awareness, no secrets in Git)
12. Route 53 and load balancers (how DNS and optional ALB fit your path; deep setup in Topic 19)
13. Operational hygiene: least-privilege IAM, key handling, no shared passwords in chat
14. AI-assisted ops workflow: draft runbooks and configs -> manually verify security groups, ports, VPC reachability, and secrets before exposing services

### Topic Project
- **Project:** BookEase Server Provisioning
- **Deliverable:** Running app process on EC2 instance with:
  - Documented SSH access (key-based) and which user runs the app
  - Security group rules explained (SSH source, app HTTP/HTTPS ports, and DB rules if applicable)
  - Reachable URL/IP demonstrating the API or a health endpoint
  - Short runbook: deploy steps, viewing logs, restarting the service
  - One-page **AWS service map** for BookEase: briefly state what **EC2**, **VPC/security groups**, **S3**, **RDS** (or on-EC2 DB), **CloudWatch**, **Secrets Manager/Parameter Store**, and **Route 53** would each be responsible for in a production-like setup (even if you only fully implement EC2 this week)
  - Explicit note on what remains for Topic 19 (domain, Nginx, SSL hardening)

---

## Topic 19: Domain, Nginx, SSL
**Duration:** Week 20  
**Outcome:** Students can attach a real domain to their server, terminate TLS safely at the edge with Nginx, and validate end-to-end HTTPS behavior suitable for a public demo or early production.

### Lessons
1. From Topic 18 to Topic 19: from raw IP/ports on EC2 to a stable hostname, reverse proxy, and trusted certificates
2. DNS record mapping (`A`/`AAAA`, `CNAME`, TTL, propagation; registrar vs Route 53 mental model)
3. Nginx reverse proxy setup (upstream to FastAPI/Node, `proxy_pass`, headers, timeouts; static files vs API routes where relevant)
4. HTTPS with Let’s Encrypt (Certbot HTTP-01 or DNS-01 awareness; certificate renewal and automation concept)
5. TLS hygiene (redirect HTTP to HTTPS, modern cipher suites at awareness level, optional security headers)
6. Deployment validation checklist (curl/browser checks, API behind HTTPS, websocket notes if used, common failure modes: DNS, firewall, Nginx syntax)
7. AI-assisted ops workflow: generate Nginx/Certbot steps -> verify configs manually before reload -> never paste private keys into chat

### Topic Project
- **Project:** Production BookEase Live
- **Deliverable:** Live HTTPS domain-backed application with:
  - Public URL using your domain (not only an IP) and valid TLS in the browser
  - Documented Nginx site config (file path or sanitized snippet in the repo/README)
  - Documented certificate issuance and **renewal** plan (cron/systemd timer or platform equivalent)
  - Smoke tests: health or main API route over HTTPS plus one frontend route if applicable
  - Short note on what you would harden next (rate limits, WAF, CDN—preview only)

---

## Topic 20: CI/CD + Modern Deployment Awareness
**Duration:** Week 21  
**Outcome:** Students can automate testing and deployment with clear separation of secrets and environments, and choose sane hosting paths for frontend vs backend in real projects.

### Lessons
1. From Topic 19 to Topic 20: repeat safe releases with automation instead of manual SSH edits for every change
2. CI/CD concepts (continuous integration vs continuous delivery/deployment, build → test → deploy stages, rollback mindset)
3. GitHub Actions deployment pipeline (workflows, jobs, runners, artifacts, branch triggers)
4. Secrets and environment handling (GitHub encrypted secrets, OIDC to cloud providers at awareness level, never commit `.pem` or API keys)
5. Patterns for deploying to your stack (for example: SSH to EC2 + restart, Docker build/push, or platform-native deploy hooks)
6. Platform overview: Vercel, Railway, Render, Fly.io (strengths, limits, pricing intuition, what runs where for SPA + API)
7. “When to use what” deployment decision matrix (team size, budget, traffic, compliance, latency, ops burden)
8. AI-assisted CI/CD: draft workflows -> review triggers and secret scopes -> validate with a test branch before merging

### Topic Project
- **Project:** Auto-Deploy Setup
- **Deliverable:** Code push triggers deployment automatically with:
  - A working GitHub Actions workflow (or equivalent CI) wired to the repo
  - At least one automated step beyond deploy (for example: run tests or lint, or build artifacts)
  - Documented required secrets/env vars **by name** (values stored only in GitHub/platform, not in the repo)
  - One successful run log/screenshot or link to workflow run
  - Brief comparison note: why this path vs a fully managed platform for BookEase

---

## Topic 21: AI Integration in Product
**Duration:** Week 22  
**Outcome:** Students can add LLM-backed features to BookEase safely: secure keys, clear API design, user-facing UX, basic guardrails, and cost-aware operation—not demo-only glue code.

### Lessons
1. From Topic 20 to Topic 21: ship AI features through the same deployment and secrets discipline (env vars, CI, no keys in frontend bundles)
2. LLM API basics (providers, API keys, models, tokens, rate limits, streaming vs single-shot at awareness level)
3. Prompt design for product use cases (system vs user messages, constraints, output format, few-shot patterns when needed)
4. Structured outputs and validation (JSON schema / Pydantic parsing of model output; handling refusals and malformed responses)
5. FastAPI AI endpoints (request/response models, timeouts, error mapping, optional background tasks)
6. React integration (chat UI, loading/error states, optimistic vs confirmed updates; optional streaming/SSE awareness)
7. AI guardrails (prompt injection basics, PII minimization, logging redaction, abuse handling mindset)
8. Cost and reliability (token estimates, caching strategy awareness, fallbacks when the API is down)
9. AI-assisted development workflow: generate prompts and handlers -> always verify outputs with tests and manual edge cases

### Topic Project
- **Project:** BookEase AI Assistant
- **Deliverable:** Live chatbot + recommendation feature with:
  - Backend route(s) secured with server-side API keys (never exposed in client build)
  - User-visible loading and error states in React
  - At least one guardrail or policy choice documented (what you refuse, truncate, or omit)
  - Basic cost or usage note (rough token/model choice rationale)
  - Test or manual QA checklist for bad inputs and empty states
  - GitHub commit history with meaningful commit messages

---

## Topic 22: Capstone Build & Demo
**Duration:** Week 23  
**Outcome:** Students can scope, build, deploy, and present an independent full-stack product that combines BookEase-era skills (React+TS, FastAPI, DB, auth, deploy, tests) with at least one clear AI-enabled feature.

### Lessons
1. From Topic 21 to Topic 22: treat AI as one product capability inside a reliable core—stability, security, and UX come first
2. Capstone planning and scope control (user stories, must-have vs nice-to-have, riskiest assumptions first)
3. Feature implementation sprint (vertical slices, trunk-based or short-lived branches, integration checkpoints)
4. Final QA and mobile audit (regression list, edge cases, performance sanity, accessibility spot-checks)
5. Deployment and presentation prep (staging vs prod mindset, smoke tests, demo script, rollback plan)
6. Demo storytelling: problem, user, architecture one-pager, trade-offs, and known limitations

### Topic Project
- **Project:** HireLocal (AI-powered marketplace)
- **Deliverable:** Live full-stack product + demo presentation with:
  - Public HTTPS URL(s) for frontend and API (or justified single-host proxy setup)
  - Core flows working end-to-end (browse/search, book or hire equivalent, auth if in scope)
  - At least one AI feature that is demonstrably connected to real API behavior (not mocked-only)
  - README: setup, env vars (by name), run instructions, architecture sketch
  - 5–8 minute demo recording or live session with slides/architecture diagram
  - Honest “phase 2” backlog tied to user value

---

## Topic 23: Career, Freelancing, Entrepreneurship Launch
**Duration:** Week 24  
**Outcome:** Students leave with recruiter-ready materials, a credible public footprint, and a practical go-to-market plan for freelancing or a lean startup—grounded in proof from the capstone, not generic claims.

### Lessons
1. From Topic 22 to Topic 23: turn shipped work into evidence (case study, metrics, repos, demos)
2. Resume and GitHub portfolio polishing (impact bullets, stack tags, ATS readability; READMEs that prove ownership)
3. LinkedIn profile alignment (headline, About, featured projects, activity plan at a sustainable cadence)
4. Fiverr/Upwork profile setup (niche, packages, portfolio pieces, response-time expectations)
5. Proposal writing and pricing basics (scoping questions, milestones, change requests, deposits, hourly vs fixed)
6. First client outreach strategy (warm intros, DMs, local businesses, outreach templates—ethical, non-spam)
7. Interview and take-home prep (system design lite, debugging narrative, talking through BookEase/HireLocal trade-offs)
8. MVP-to-startup roadmap (feedback loops, landing page tests, legal/tax awareness at “know what you don’t know” level)

### Topic Project
- **Project:** Market Launch Kit
- **Deliverable:** Resume + portfolio + freelance profile + 3 proposals with:
  - One-page resume tailored to full-stack + AI-enabled product work
  - GitHub profile/readme polish and 1–2 flagship repos (HireLocal or strongest project) with screenshots and live links
  - Complete freelance marketplace profile (bio, skills, pricing starter packages)
  - Three tailored proposals for realistic job posts (different client types or budgets)
  - Short “next 30 days” plan: outreach targets, weekly hours, and one measurable goal (applications sent, portfolio hits, first call)

---

## Recurring LMS Blocks (Add to Every Week)

Each block should have a **short prompt**, **estimated time**, **submission type**, and a simple **done checklist** in your LMS.

1. **Debugging Lab (weekly):** One deliberately broken scenario (frontend, API, or DB) to diagnose with console/logs/SQL—submission: root cause + fix summary + prevention note.  
2. **Applied Logic Drill (weekly):** Small coding or data task tied to BookEase/realistic domain data—submission: working snippet + 2 test cases.  
3. **Mobile Review Gate (weekly):** Mandatory phone/tablet pass on the current build—submission: checklist + 1 screenshot of the worst issue found (or “no issues” with device noted).  
4. **Progress Demo (weekly):** 2–3 minute demo of what changed since last week—submission: 60-second Loom or live micro-demo + one lesson learned.  
5. **AI Reflection (weekly):** What AI helped with, what was coded or verified manually, and one mistake AI would have caused if unchecked—submission: 5–8 sentences.

---

## Suggested LMS Data Fields (for each Topic)

- Topic Title
- Duration
- Prerequisite
- Lessons
- Assignment/Project
- Submission Type (GitHub link / Live URL / Video demo)
- Evaluation Rubric
- Completion Badge

---

## Suggested Assessment Rubric (Simple)

- **40%** Project works end-to-end  
- **20%** Code clarity and structure  
- **15%** Debugging ability (can explain fix)  
- **15%** Mobile responsiveness  
- **10%** Communication (demo/presentation)

