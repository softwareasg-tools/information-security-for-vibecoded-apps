# Vibesec Auditor: Autonomous AI Security Agent 🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AppSec](https://img.shields.io/badge/Security-AppSec-blue.svg)]()
[![AI Prompt](https://img.shields.io/badge/AI-Agent_Prompt-purple.svg)]()

> An autonomous **Application Security (AppSec) prompt and skill module** for AI coding assistants (Google Antigravity, Cursor, Copilot, Claude, Windsurf). Converts AI-generated apps into secure production software.

---
### ⭐️ Support the Project
**If this skill helps you secure your application, please consider leaving a Star on this repository!** 
It takes one click, helps other builders find this tool, and is incredibly appreciated.
---

## Why This Exists (For the Vibe Coders)

If you are building with AI, you already know how powerful it is to turn ideas into working software. 

This skill helps you take the next crucial step: making sure the application you built is safe, reliable, and ready for real users. **You do not need to be a cybersecurity expert.**

Whether you are:
- A **founder** building your first SaaS product
- A **domain expert** creating an internal business tool
- A **designer** turning an idea into a web app
- A **business professional** automating your workflow
- A **developer** experimenting with AI-assisted coding and rapid prototyping

...this skill acts as your automated **DevSecOps partner**. It reviews your application like an experienced security engineer would, identifies hidden vulnerabilities, and helps you fix them before they become real problems.

---

## Installation & Usage Guide

### 🪐 For Google Antigravity Users
Clone this repository directly into your global skills folder. Antigravity will automatically detect the `SKILL.md` YAML frontmatter.
```bash
cd ~/.gemini/config/skills
git clone https://github.com/softwareasg-tools/information-security-for-vibecoded-apps.git infosec-vibecoded-apps
```

### 🖱️ For Cursor / Windsurf Users
AI coding has made it possible for anyone with domain knowledge to build powerful web applications. Add this skill to your project so your AI coding assistant can help you think about security while you build.

Copy the contents of `SKILL.md` into your `.cursorrules` or `.windsurfrules` file at the root of your project.

### 🤖 For ChatGPT / Claude / GitHub Copilot
You can use this automated code review prompt with any LLM by sharing the contents of `SKILL.md`. Start your chat with:

> *"Adopt this security engineer persona. Review my application codebase and help me identify and fix security risks. My codebase is located at [PATH]."*

The AI assistant will analyze your application, auto-detect your technology stack, and guide you through patching security flaws.

---

## What This Skill Does

This is not a generic vulnerability scanner. It is an **LLM-optimized security prompt** designed specifically for the new era of AI-assisted development (vibe coding), where people with deep business expertise can build software faster than ever before. 

The skill helps answer critical pre-launch questions:
* "Is my SaaS app safe from hackers before I launch it?"
* "Did my AI coding assistant accidentally introduce security loopholes?"
* "Could users access data (IDOR) they shouldn't see?"
* "Are my REST APIs, GraphQL, and databases protected?"
* "Are my API keys and credentials safe from leaks?"

---

## 🔍 The 12-Phase Security Review Journey

When triggered, the AI agent performs a structured **AppSec audit** across 12 critical vectors:

1. **Repository Security Scan:** Finds exposed secrets, risky dependencies, and unsafe `.env` configurations.
2. **AI-Generated Code Risk Assessment:** Identifies common security hallucinations and mistakes introduced during rapid AI development.
3. **Authentication Security Testing:** Reviews login flows, JWT sessions, passwords, and identity controls.
4. **Authorization Testing (RBAC):** Verifies users can only access their own tenant data (prevents IDOR).
5. **API Security Testing:** Checks whether your application's endpoints are rate-limited and protected.
6. **Injection Testing:** Looks for SQLi, NoSQLi, XSS, and dangerous data handling issues.
7. **Frontend Security Testing:** Reviews browser-side risks, CSP headers, and exposed client secrets.
8. **Database Security Testing:** Checks data access controls and database exposure limits.
9. **Cloud Security Testing:** Reviews hosting, IAM permissions, and cloud configuration (AWS, Vercel, Supabase, Firebase).
10. **Infrastructure Security:** Checks Docker containers, Kubernetes, and deployment setup.
11. **Logging and Monitoring:** Ensures application errors don't leak PII or stack traces.
12. **Security Regression Testing:** Creates automated safeguards so vulnerabilities do not return.

---

## Built for the Vibe Coding Era

Great software has always started with great ideas. AI has fundamentally changed *who* can build software. **Cybersecurity should not become a barrier to creation.**

This skill exists to help builders move from:
> *"I built something amazing."*

To:
> *"I built something amazing that people can safely trust."*
