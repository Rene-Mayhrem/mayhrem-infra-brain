

# 🧠 Week 1 Plan — Developer Learning OS

## 🎯 Theme

> **Networking Foundations (DNS + HTTP)**

Why?

* Everything in DevOps/SRE depends on networking
* It feeds directly into:

  * System design (rate limiting, APIs)
  * Projects (reverse proxy, routing)

---

# ⚙️ Global Weekly Goals

You are NOT allowed to exceed this.

* 🧠 2 Class Reports
* 🏗 1 System Design
* 🚀 1 Small Project (light)
* 🧩 3–5 LeetCode problems
* 📊 1 Weekly Review

---

# 🧱 Repo-by-Repo Plan

---

## 🧠 `learning-system`

### 🎯 Goal: Build foundational understanding

### Tasks:

#### 1. Class 1 — DNS Resolution

Focus:

* Recursive vs iterative resolution
* DNS hierarchy (root, TLD, authoritative)
* Caching + TTL

---

#### 2. Class 2 — HTTP Fundamentals

Focus:

* Request/response lifecycle
* Headers
* Methods (GET, POST, etc.)
* Statelessness

---

### ⚠️ Output Required:

2 Markdown files in:

```bash
semesters/networking/
```

---

---

## 🏗 `system-design`

### 🎯 Goal: First real system thinking

### Task:

#### Design: Rate Limiter (basic version)

Focus:

* Why rate limiting exists
* Where it sits (API Gateway / backend)
* Simple approaches:

  * Fixed window
  * Token bucket (just conceptually)

---

### ⚠️ Output Required:

```bash
low-level/rate-limiter.md
```

---

---

## 🚀 `devops-portfolio`

### 🎯 Goal: First practical connection

### Task:

#### Project: Nginx Reverse Proxy (Minimal)

Scope (keep it SMALL):

* Run Nginx in Docker
* Forward traffic to a simple backend
* Understand routing behavior

---

### DO NOT:

* Add Kubernetes
* Add cloud
* Over-engineer

---

### ⚠️ Output Required:

```bash
projects/nginx-reverse-proxy/
```

With:

* Dockerfile / docker-compose
* Simple README

---

---

## 🧩 `leetcode`

### 🎯 Goal: Warm up problem-solving

### Tasks:

Do **3–5 problems**:

Focus:

* Arrays
* Hash maps

---

### Suggested types:

* Two Sum
* Valid Anagram
* Contains Duplicate

---

### ⚠️ Output Required:

Structured solutions in repo

---

---

## 🧠 `infra-brain`

This is where you **control everything**.

---

### 1. Create Weekly Plan

```bash
weekly-plans/week-01.md
```

Include:

* Theme
* Tasks (from above)

---

---

### 2. Update Dashboard

Track:

* Status of each repo
* Current bottleneck

---

---

### 3. End of Week → Weekly Review

```bash
weekly-reviews/week-01.md
```

---

# 📅 Suggested Weekly Flow (Realistic)

## 🏠 Remote Days

### Day 1

* Start DNS
* Write partial report

---

### Day 2

* Finish DNS
* Start Rate Limiter design

---

### Day 3

* HTTP fundamentals
* Continue design

---

---

## 🏢 Office Days

* Light reading (DNS / HTTP)
* 1 LeetCode per day

---

---

## 🌙 Nights

* Daily report (short)
* No heavy thinking

---

---

## Weekend (Important)

### Block 1:

* Finish Rate Limiter

### Block 2:

* Nginx project

### Block 3:

* Weekly Review

---

# 🔗 Cross-Repo Connections (MANDATORY)

This is what makes it a system.

---

## DNS / HTTP → Rate Limiter

You must connect:

* HTTP requests → rate limiting logic

---

## Rate Limiter → Nginx

Understand:

* Where rate limiting could live

---

## Nginx → HTTP

Observe:

* Headers
* Routing

---

# ⚠️ Constraints (VERY IMPORTANT)

## ❌ Do NOT:

* Start new topics
* Add complexity
* Skip writing

---

## ✅ DO:

* Finish what you start
* Keep things simple
* Focus on understanding

---

# 🧠 What Success Looks Like (End of Week)

You can:

* Explain how DNS works end-to-end
* Explain HTTP request lifecycle
* Design a basic rate limiter
* Run a reverse proxy locally
* Solve basic hash map problems

