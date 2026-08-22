# Vibesec Auditor: Autonomous AI Security Agent 🛡️

> An autonomous Application Security (AppSec) prompt and skill module for AI coding assistants (Google Antigravity, Cursor, Copilot, Claude).

## What is this?
**Vibesec Auditor** transforms your AI coding assistant into a Principal Application Security Engineer. Instead of relying on manual discovery, you simply provide your codebase path, and the AI autonomously executes a rigorous **12-Phase Security Scan**.

It bridges the gap between "AI-generated applications that work" and "Secure production-grade software."

## Features
* 🤖 **Zero-Config Discovery**: Automatically infers your frontend, backend, database, and cloud infrastructure.
* 🔍 **12-Phase Security Audit**: Covers everything from Secret Detection (Phase 1) to Cloud Security (Phase 9) and Logging (Phase 11).
* 🛡️ **AppSec Methodologies**: Checks for IDOR, Privilege Escalation, Mass Assignment, Injection, and AI-specific vulnerabilities.
* 🚫 **Strict Production Gates**: Concludes with a definitive BLOCK, CONDITIONAL, or APPROVED release decision.

## Installation

### For Google Antigravity Users
Clone this repository directly into your global skills folder. Antigravity will automatically detect the `SKILL.md` YAML frontmatter.
```bash
cd ~/.gemini/config/skills
git clone https://github.com/YOUR_USERNAME/vibesec-auditor.git infosec-vibecoded-apps
```

### For Cursor / Windsurf Users
Copy the contents of `SKILL.md` into your `.cursorrules` or `.windsurfrules` file at the root of your project.

### For ChatGPT / Claude
Simply copy the entire text of `SKILL.md`, paste it into the chat, and say:
*"Adopt this persona. My codebase is attached/located at [PATH]."*

## The 12 Phases
1. **Repository Security Scan** (Secrets, Git History, Dependencies)
2. **AI-Generated Code Risk Assessment**
3. **Authentication Security Testing**
4. **Authorization Testing** (IDOR, Privilege Escalation)
5. **API Security Testing**
6. **Injection Testing** (SQLi, NoSQLi, XSS, SSRF)
7. **Frontend Security Testing**
8. **Database Security Testing**
9. **Cloud Security Testing**
10. **Infrastructure Security** (Docker, K8s)
11. **Logging and Monitoring**
12. **Security Regression Testing**

---
*Built for the vibe-coding era.*
