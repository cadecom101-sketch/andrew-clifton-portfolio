# Andrew Clifton — Portfolio & Project Archive
**Creative Production, Practical Systems Administration, and Python Learning Journey**

[![Path: Python Foundations](https://img.shields.io/badge/Path-Python%20Foundations-blue.svg)](#1-technical-education--python-foundations)
[![Methodology: Radical Transparency](https://img.shields.io/badge/Methodology-Radical%20Honesty%20%26%20Transparency-green.svg)](#transparency--ai-tooling-statement)
[![Status: Active Learner & Builder](https://img.shields.io/badge/Status-Active%20Learner%20%26%20Builder-orange.svg)](#about-me)

---

## About Me

I am an independent builder and career switcher actively studying foundational computer science and Python programming (started July 2026). My background spans commercial audio production, practical home/workstation systems administration, business research, and creative digital media.

I use modern AI tools (Claude, ChatGPT, Codex) as learning accelerators and prototyping assistants. I do not claim to be a senior software engineer or an enterprise systems architect. This portfolio is an honest, factual record of what I have actually built, what I have directed, what I am learning, and how I approach problem-solving.

---

## Transparency & AI Tooling Statement

> **Honesty First:** Many tech portfolios today present AI-generated code and theoretical architectures as if the author wrote them from scratch. I do not do that.
> 
> * **Personal Work:** Music writing and production, hardware network configuration, OS troubleshooting, business research, and daily Python study are my own direct work.
> * **AI-Assisted Prototypes:** In software projects like *RuneRun*, I acted as the game designer, creative director, and tester—directing AI assistants to generate the JavaScript and audio synthesis code while managing the feature roadmap.
> * **Active Learning:** I am actively working through core Python syntax, data structures, and algorithms to build durable, unassisted programming literacy.

---

## Project Catalog

### 1. Technical Education & Python Foundations
* **Status:** Active Study (Daily disciplined warm-ups and exercises)
* **Intake Date:** July 14, 2026
* **Curriculum:** Mimo Python Developer Path, Coursera, Codecademy, and deliberate recall practice.
* **Topics Mastered & In Progress:**
  - Variables, state tracking, and assignment mechanics (`score = score + 3`).
  - Primitive data types (integers, floats, strings, booleans) and type coercion.
  - Conditional branching (`if`, `elif`, `else`) and logical operators.
  - Loops (`while`, `for`) and iteration over collections.
  - Writing clean, modular functions with return values.
  - Independent debugging from blank files without autocomplete or AI crutches.
* **Goal:** Complete the 115-item Mimo certification and build employable, practical scripting skills from the ground up.

---

### 2. Workstation Systems Administration & Storage Recovery
* **Domain:** Windows 10 OS Administration, Storage Forensics, VSS Backup
* **Machine:** HP Pavilion Desktop (`desktop-366fofl`), Samsung NVMe SSD (118 GB) + Toshiba SATA HDD (1 TB)
* **What Happened:**
  - The workstation's primary NVMe SSD hit a critical storage floor (~10.5 GB free), threatening daily operations.
  - Initial automated AI cleanup scripts made false claims ("0% risk, 14.36 GB freed") while actually breaking Puppeteer's Chrome binaries, setting ineffective environment variables, and failing to stop the Windows pagefile from reabsorbing the freed space.
  - I halted execution, ran an independent forensic audit, and directed a multi-phase remediation plan.
* **Actions Taken & Verified:**
  - Enabled Windows System Protection (VSS) and created a verified restore point before making any system changes.
  - Safely eliminated unneeded hibernation files on an A/C-powered desktop (`powercfg /hibernate off`), freeing **+3.15 GB**.
  - Pruned stale Windows Update download caches and multi-profile Chrome browser caches, freeing **+4.70 GB** with zero loss of logins or bookmarks.
  - Addressed root causes by capping `pagefile.sys` (4 GB on NVMe SSD, 8 GB overflow on HDD) and executing a DISM Component Store cleanup (**-3.13 GB** unlinked).
  - Repopulated Puppeteer and Playwright browser binaries onto the secondary HDD (`D:\caches\`) and permanently locked tool cache configs (`pip.ini`, `.npmrc`, `.puppeteerrc.cjs`).
* **Final Result:** Reclaimed **+15.57 GB** of safe headroom, bringing the NVMe boot drive from **10.51 GB (8.9%) to 26.08 GB (22.1%)** free space without breaking application sandboxes or corrupting multi-user accounts.

---

### 3. Home Network Optimization (Bufferbloat Mitigation)
* **Domain:** Network Infrastructure, QoS Traffic Shaping, Hardware Configuration
* **Hardware:** CenturyLink C3000Z Modem / Gateway
* **Problem:** High latency spikes and jitter during concurrent video streaming and interactive usage (bufferbloat).
* **What Was Done:**
  - Audited local gateway metrics and conducted benchmark latency testing.
  - Configured custom Quality of Service (QoS) bandwidth limits (DevMax Clamp) to throttle upstream/downstream saturation points.
  - Documented complete configuration changes and rollback runbooks in a formal technical guide.
* **Result:** Stabilized ping times under heavy load and eliminated latency spikes across all household devices.

---

### 4. Commercial Music Production — "Losing Against Ghosts"
* **Domain:** Audio Engineering, Commercial Music Distribution, Digital Rights Operations
* **Catalog:** 6 remastered studio tracks (Alternative / Heavy Rock)
* **Distribution:** Released globally across Spotify, Apple Music, Amazon, YouTube Music via DistroKid ("Losing Ghosts" label).
* **Operations & Results:**
  - Directed mixing, mastering, metadata tagging, and cover art production.
  - Enforced digital rights protection via YouTube Content ID and Meta Rights Manager.
  - Built an organic discovery signal of **5,854 HyperFollow presaves/followers** on lead single *"Ashes Between Us"*.
  - Authored standard operating manuals for release package packaging and permanent rights accrual.

---

### 5. Game Prototyping & Creative Direction — "RuneRun" (Version 14)
* **Domain:** Creative Direction, Game Design, AI Pair-Programming
* **Project:** Retro HTML5 Canvas 2D action game with procedural Web Audio.
* **Andrew's Actual Role:**
  - Conceived the gameplay loop, level mechanics, and audio themes.
  - Directed AI assistants (Claude, Codex) to write the vanilla JavaScript game engine, collision math, and Web Audio synthesis code.
  - Managed feature roadmaps, tested every version through 14 iterative releases, and validated stability using automated test runners (161 test assertions).
* **Key Learning:** Learned how to evaluate code generated by AI, spot regression bugs, manage feature scope, and maintain git version checkpoints.

---

### 6. Generative Media Framework — "Nightcore Artist Project"
* **Domain:** Creative Operations, Digital Artist IP, Asset Organization
* **Project:** Commercial generative audio and character illustration pipeline.
* **What Was Done:**
  - Created a digital artist persona and produced 5 songs using Suno audio generation tools.
  - Built an 8-tier folder structure to solve the #1 issue in generative AI projects: prompt drift, lost assets, and unorganized variations.
  - Maintained reference bibles for character illustration consistency across releases.

---

### 7. Business Feasibility & Operations Research
* **Domain:** Real Estate Feasibility, Commercial Finance Modeling
* **Projects:**
  - **Central Home Properties OS:** Researched wholesale real estate deal intake procedures, lead tracking spreadsheets, and Section 8 Housing Choice Voucher compliance checklists.
  - **Self-Storage Commercial Feasibility:** Explored 5-scenario financial sensitivity models and zoning research for commercial storage development.
* **What Was Done:** Researched industry standards, organized legal/zoning documentation into structured reference folders, and created practical operational checklists.

---

## Contact & Links
* **GitHub:** [cadecom101-sketch](https://github.com/cadecom101-sketch)
* **Location:** Arkansas, USA
* **Current Focus:** Python programming foundations, practical computer science, and transparent, AI-assisted project building.
