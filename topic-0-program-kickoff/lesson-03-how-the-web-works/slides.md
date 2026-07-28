# Lesson 03 — How the Web Works (Deep Beginner Version)

**Topic 0 | Week 1**

---

## Slide 1 — Title

# How the Web Works
### Client, server, IP, domain, DNS, and all players

*Future full stack developers must know the full chain.*

---

## Slide 2 — Outcome

# By end of this class

You can explain clearly:

1. Client ↔ server request/response using IP  
2. Why sharing raw IP is a problem for real products  
3. Domain parts and domain ownership process  
4. DNS players: registrar, registry, nameserver, resolver  
5. Full user flow from typing URL to seeing page  

---

## Slide 3 — Core actors

# Who are client and server?

| Actor | Meaning |
|------|---------|
| **Client** | User device + browser (Chrome/Edge/Firefox/Safari) |
| **Server** | Powerful internet-connected computer running app code |

When we deploy our web app, code runs on a **server**.  
Users (clients) interact with that server over the internet.

---

## Slide 4 — IP-first cycle (no domain yet)

# Start simple: only IP address

Assume server IP is `203.0.113.10`

1. Client sends request to that IP  
2. Server receives request  
3. Backend processes logic/database  
4. Server sends response (HTML/CSS/JS/JSON)  
5. Browser renders UI for user  

---

## Slide 5 — Request / response picture

# Request-response model

```
Client (browser)
   ── HTTP request ──>  Server (IP: 203.0.113.10)
   <─ HTTP response ──  Server
```

This is the base of all web apps.  
Domain and DNS are convenience layers on top.

---

## Slide 6 — Why not distribute only IP?

# Problems if customers use raw IP

- Hard to remember (`203.0.113.10`)  
- Looks untrusted for business users  
- IP can change during hosting migration  
- One server can host many apps (needs names)  
- Branding impossible (no `bookease.com`)  
- Harder SSL cert management for user-friendly URLs  

---

## Slide 7 — Real business impact

# If you market with IP only

Imagine ads saying:  
**“Visit our site: 203.0.113.10”**

Users will ask:

- “Is this safe?”  
- “Is this phishing?”  
- “How will I remember this?”  

So businesses use **domains** as human-friendly identity.

---

## Slide 8 — Domain basics

# Domain = human-readable address

Examples: `google.com`, `amazon.in`, `bookease.com`

Domain points to server IP through DNS.  
Users remember names; machines still connect using IP.

**Analogy:** Contact name in phone, actual number in backend.

---

## Slide 9 — Parts of a domain

# Domain structure

Example: `api.shop.bookease.com` *(sample format)*

| Part | Example | Meaning |
|------|---------|---------|
| Subdomain | `api` / `shop` | Specific service/section |
| Second-level domain | `bookease` | Brand/project name |
| Top-level domain (TLD) | `.com` | Ending managed globally |

Common TLDs: `.com`, `.in`, `.org`, `.net`, `.dev`

---

## Slide 10 — Domain ecosystem players

# Who manages domain names?

1. **Registrant** — person/company buying domain  
2. **Registrar** — seller where you buy domain  
3. **Registry** — operator for each TLD (`.com`, `.in`)  
4. **ICANN** — global coordination body for DNS policies  

You usually interact with registrar; registrar talks to registry.

---

## Slide 11 — Popular registrars

# Registrar examples

- GoDaddy  
- Namecheap  
- Google Domains / Squarespace Domains  
- Hostinger  
- BigRock

Registrar gives control panel to set DNS records and nameservers.

---

## Slide 12 — DNS players in lookup

# DNS lookup actors (important)

1. **Client/browser** starts lookup  
2. **Recursive resolver** (ISP / Cloudflare / Google DNS)  
3. **Root nameserver**  
4. **TLD nameserver** (`.com`, `.in`)  
5. **Authoritative nameserver** for your domain  

Final result: IP address returned to client.

---

## Slide 13 — Nameserver types

# What is a nameserver?

A nameserver answers DNS questions for a domain.

Types students should know:

- **Recursive resolver** — finds answer for client  
- **Authoritative nameserver** — stores final domain records  

Common DNS providers (authoritative):
- Cloudflare DNS  
- AWS Route 53  
- GoDaddy DNS  

---

## Slide 14 — DNS records (quick intro)

# Important record types

| Record | Purpose |
|--------|---------|
| **A** | Domain → IPv4 address |
| **AAAA** | Domain → IPv6 address |
| **CNAME** | Alias one name to another |
| **MX** | Mail server for domain email |
| **TXT** | Verification/SPF/security text data |

Web apps mostly start with **A/AAAA/CNAME**.

---

## Slide 15 — Full URL-to-page flow

# End-to-end cycle (with all players)

1. User types `https://bookease.com`  
2. Browser asks recursive resolver  
3. Resolver queries root → TLD → authoritative nameserver  
4. Gets IP for `bookease.com`  
5. Browser connects to server IP  
6. HTTPS handshake + request sent  
7. Server backend processes and returns response  
8. Browser renders frontend to user  

---

## Slide 16 — Client-server in full stack context

# What runs where?

| Layer | Usually runs on |
|------|------------------|
| Frontend rendering | Client browser |
| Backend API | Server |
| Database | Server/private network |

So yes: web application code must be hosted on a powerful internet server for real users.

---

## Slide 17 — Mini case: BookEase

# BookEase example

Deploy backend + frontend on cloud server.  
Server IP: `198.51.100.25` (example)

But customers use:
`https://bookease.com`

DNS maps domain → IP silently.

---

## Slide 18 — Activity

# Draw the chain (pairs)

Draw and label:

Client → Resolver → Root NS → TLD NS → Authoritative NS → Server → Client

Also mark:
- where domain is bought (registrar)  
- where A record is stored (authoritative DNS)  

---

## Slide 19 — Interview line

# Say it like a professional

> "Our app runs on an internet server with an IP. Users access it via a domain. DNS resolves that domain through resolver, root, TLD, and authoritative nameservers, then the browser sends HTTPS requests and renders the server response."

---

## Slide 20 — Takeaways

# Remember

1. Client and server communicate via request/response  
2. IP-only access is technical but poor for real users  
3. Domains provide human-friendly identity  
4. Registrars, registries, and nameservers are different roles  
5. DNS translates names to IP so web apps are usable at scale  

**Next:** Files, folders, terminal, localhost, and ports
