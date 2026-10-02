# GitHub Profile README — Instructions for Claude

## Context

**User:** Kishor — Full-stack developer (2 years) at Biz Secure Labs (Net Protector Antivirus, Pune).  
**Main project:** CareerOS — an AI-powered career learning platform (Laravel 13, React, TypeScript, Ollama AI).  
**Goal:** Build a professional GitHub profile that reflects real skills and showcases CareerOS.

---

## What Claude needs to do when asked to write the GitHub README

When Kishor asks to write or update his GitHub profile README, Claude must:

1. **Ask for these details first** (if not already known):
   - Exact GitHub username
   - LinkedIn URL or email for contact section
   - Any other projects to feature besides CareerOS
   - Preferred theme: dark / light / minimal

2. **Write a complete `README.md`** — copy-paste ready, no placeholders left unfilled except GitHub username and links Kishor must supply himself.

3. **Follow the structure below exactly** — in this order, nothing skipped.

---

## Required README Structure

### Section 1 — Header / Intro
- One punchy line: who he is + what he builds
- No fluff, no "passionate developer" clichés
- Add a wave emoji or keep it clean — Kishor's call

```markdown
# Hi, I'm Kishor 👋
Full-stack developer building tools that make learning and security better.
```

### Section 2 — What I'm Building (Featured Projects)
- **CareerOS** must be the first and most prominent project
- Include: what it does (1 sentence), tech stack used, live link if available
- Format as a table or card-style list — NOT a bullet dump

```markdown
## What I'm Building

| Project | Description | Stack |
|---------|-------------|-------|
| [CareerOS](link) | AI-powered career learning platform with quizzes, hints, and level progression | Laravel · React · TypeScript · Ollama |
| [Net Protector](link) | Antivirus tooling at Biz Secure Labs | ... |
```

### Section 3 — Tech Stack (Visual Badges)
Use shields.io badges — `style=for-the-badge`. Group them by category.

**Backend:**
```markdown
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
```

**Frontend:**
```markdown
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
```

**Tools:**
```markdown
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
```

### Section 4 — GitHub Stats Cards
Always use `theme=tokyonight` unless Kishor requests otherwise.
Replace `YOUR_USERNAME` with his actual GitHub username.

```markdown
## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true)
```

> Note: Stats cards only show public repo data. Remind Kishor to make relevant repos public.

### Section 5 — Currently Working On
Keep this short and honest — 1-2 lines max.

```markdown
## Currently Building
- CareerOS v1 — finishing the points, AI hints, and level exam system
```

### Section 6 — Contact
One line. No walls of icons.

```markdown
## Let's Connect
[LinkedIn](https://linkedin.com/in/YOUR_HANDLE) · [Email](mailto:YOUR_EMAIL)
```

---

## Rules Claude must follow when writing this README

- **No fake projects** — only list real things Kishor has actually built
- **No buzzword soup** — avoid "passionate", "enthusiastic", "love to code", etc.
- **No empty sections** — if a section has nothing real to put, skip it entirely
- **Keep it scannable** — a recruiter should understand Kishor's profile in 15 seconds
- **Don't over-emoji** — max 2-3 emojis total in the whole file
- **CareerOS always goes first** — it is the strongest project
- **Write in Kishor's voice** — direct, technical, no corporate-speak

---

## How to publish it

1. Go to github.com → New repository
2. Name it **exactly** the GitHub username (case-sensitive)
3. Set to **Public**
4. Check **"Add a README file"**
5. Replace the README content with the generated file
6. Commit → done. Profile updates instantly.

---

## Making repos look good (Claude should advise this too)

For each project repo Kishor pushes publicly:

- Add a **description** in the repo's About section (one sentence)
- Add **topics/tags**: e.g. `laravel`, `react`, `typescript`, `ai`, `saas`, `mysql`
- Add a **live demo URL** if deployed
- Write a proper `README.md` inside the repo with:
  - What the project does
  - Tech stack
  - How to run locally (setup steps)
  - Screenshots if possible

---

## Quick reference — useful tools

| Tool | Purpose | URL |
|------|---------|-----|
| shields.io | Tech stack badges | https://shields.io |
| github-readme-stats | Stats + language cards | https://github.com/anuraghazra/github-readme-stats |
| streak-stats | Contribution streak card | https://streak-stats.demolab.com |
| readme.so | Visual README builder | https://readme.so |
| skill-icons | Prettier tech icons | https://skillicons.dev |

---

## Example — skill-icons alternative to shields.io

If Kishor prefers icon grid over badge pills:

```markdown
[![My Skills](https://skillicons.dev/icons?i=laravel,php,react,ts,mysql,git,linux,vite)](https://skillicons.dev)
```

This renders a clean icon row — more visual, less text-heavy.
