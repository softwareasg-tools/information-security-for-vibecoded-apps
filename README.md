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

## 🛡️ Built for Vibe Coders

AI tools are fantastic at writing code that works, but they consistently ignore secure architecture. This project exists to close that loop. This engine was built to solve that exact issue. It brings rigorous, enterprise-grade security engineering directly into your rapid AI workflow.

Created by a **Certified Information Systems Auditor (CISA, ISACA, USA)** with over 15 years of hands-on experience in enterprise Application Security, threat modeling, and DevSecOps.

## 📋 Anchored in Global Infosec Standards

The 12-Phase Autonomous Scan strictly enforces the most widely respected cybersecurity frameworks in the industry. The agent's logic is explicitly mapped to:
* **OWASP Top 10 (2021):** Comprehensive coverage against the most critical web application security risks (Injection, Broken Access Control, Cryptographic Failures).
* **OWASP ASVS (Application Security Verification Standard):** Automated checks aligned with Level 1 and Level 2 verification requirements for production readiness.
* **NIST SSDF (Secure Software Development Framework):** Enforces secure-by-design principles natively within your AI-assisted CI/CD pipeline.
* **MITRE ATT&CK®:** Proactive defense against known adversary tactics, techniques, and procedures targeting cloud and API infrastructure.

## 📊 The VibeSec Audit Benchmark (VAS-100)

To provide quantifiable security metrics, the auditor evaluates your codebase against 80+ security controls to calculate your **VibeSec Audit Score (VAS-100)**. 

The application is graded across 7 weighted domains (Authentication, Authorization, API Security, Cloud Configuration, etc.) to generate a score out of 100. 

🏆 **The Gold Standard:** Applications that score **85/100 or higher** with zero "Critical" findings demonstrate robust resilience equivalent to passing a standard enterprise penetration test. Applications falling below this benchmark will automatically trigger a **BLOCK RELEASE** decision, providing you with exact, minimal code fixes to reach compliance.

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
