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
**Outcome:** API confidence through rebuild.

### Lessons
1. API design checklist
2. Validation and error handling
3. Testing endpoints in Swagger/Postman
4. Refactor and cleanup

### Topic Project
- **Project:** Mini Inventory/Orders API
- **Deliverable:** Independent API with clean endpoints

---

## Topic 13: PostgreSQL & SQL
**Duration:** Week 14  
**Outcome:** Students can store and query persistent data.

### Lessons
1. Tables, rows, primary/foreign keys
2. Basic SQL queries
3. Joins and filtering
4. Database schema design for BookEase

### Topic Project
- **Project:** BookEase Database Setup
- **Deliverable:** DB schema + sample data + key queries

---

## Topic 14: ORM + Migrations + Full Stack Persistence
**Duration:** Week 15  
**Outcome:** Backend uses real DB persistence.

### Lessons
1. SQLAlchemy models
2. Alembic migrations
3. DB session patterns
4. Replace in-memory storage with Postgres

### Topic Project
- **Project:** Persistent BookEase API
- **Deliverable:** Fully DB-backed backend

---

## Topic 15: Docker + Local Full Stack Run
**Duration:** Week 16  
**Outcome:** Students can run full app reliably.

### Lessons
1. Docker basics
2. Dockerfile fundamentals
3. Docker Compose for app + DB
4. Environment config for containers

### Topic Project
- **Project:** Containerized BookEase
- **Deliverable:** One-command local startup

---

## Topic 16: Git, GitHub, Team Workflow
**Duration:** Week 17  
**Outcome:** Students can work like real software teams.

### Lessons
1. Git core commands
2. Branching strategy
3. Pull requests and review flow
4. Agile basics (tickets, standups, sprints)
5. Professional README writing

### Topic Project
- **Project:** Team Workflow Simulation
- **Deliverable:** PR-based feature merge with code review

---

## Topic 17: Testing Basics
**Duration:** Week 18  
**Outcome:** Students can verify software quality.

### Lessons
1. Testing mindset for beginners
2. API test cases in Postman
3. Pytest basics for FastAPI
4. Frontend testing awareness (React Testing Library intro)
5. Bug report writing

### Topic Project
- **Project:** BookEase Test Pack
- **Deliverable:** Test checklist + Postman collection + basic pytest file

---

## Topic 18: AWS EC2 Deployment (Deep Learning)
**Duration:** Week 19  
**Outcome:** Students understand real server deployment.

### Lessons
1. AWS core concepts (EC2/IAM/security groups)
2. Linux server basics + SSH
3. Server setup for app runtime
4. Production config basics

### Topic Project
- **Project:** BookEase Server Provisioning
- **Deliverable:** Running app process on EC2 instance

---

## Topic 19: Domain, Nginx, SSL
**Duration:** Week 20  
**Outcome:** Students can make production app publicly accessible.

### Lessons
1. DNS record mapping
2. Nginx reverse proxy setup
3. HTTPS with Let’s Encrypt
4. Deployment validation checklist

### Topic Project
- **Project:** Production BookEase Live
- **Deliverable:** Live HTTPS domain-backed application

---

## Topic 20: CI/CD + Modern Deployment Awareness
**Duration:** Week 21  
**Outcome:** Students can automate release and compare deployment options.

### Lessons
1. CI/CD concepts
2. GitHub Actions deployment pipeline
3. Secrets and environment handling
4. Platform overview: Vercel, Railway, Render, Fly.io
5. “When to use what” deployment decision matrix

### Topic Project
- **Project:** Auto-Deploy Setup
- **Deliverable:** Code push triggers deployment automatically

---

## Topic 21: AI Integration in Product
**Duration:** Week 22  
**Outcome:** Students can ship AI-powered product features.

### Lessons
1. LLM API basics
2. Prompt design for product use cases
3. FastAPI AI endpoints
4. React chatbot UI integration
5. AI guardrails and cost basics

### Topic Project
- **Project:** BookEase AI Assistant
- **Deliverable:** Live chatbot + recommendation feature

---

## Topic 22: Capstone Build & Demo
**Duration:** Week 23  
**Outcome:** Students can independently build and launch a full product.

### Lessons
1. Capstone planning and scope control
2. Feature implementation sprint
3. Final QA and mobile audit
4. Deployment and presentation prep

### Topic Project
- **Project:** HireLocal (AI-powered marketplace)
- **Deliverable:** Live full-stack product + demo presentation

---

## Topic 23: Career, Freelancing, Entrepreneurship Launch
**Duration:** Week 24  
**Outcome:** Students leave market-ready.

### Lessons
1. Resume and GitHub portfolio polishing
2. Fiverr/Upwork profile setup
3. Proposal writing and pricing basics
4. First client outreach strategy
5. MVP-to-startup roadmap

### Topic Project
- **Project:** Market Launch Kit
- **Deliverable:** Resume + portfolio + freelance profile + 3 proposals

---

## Recurring LMS Blocks (Add to Every Week)

1. **Debugging Lab (weekly):** one broken scenario to diagnose and fix  
2. **Applied Logic Drill (weekly):** small coding logic task from project data  
3. **Mobile Review Gate (weekly):** mandatory phone/tablet checks  
4. **Progress Demo (weekly):** every student presents 2–3 minutes  
5. **AI Reflection (weekly):** what AI helped with, what was coded manually

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

