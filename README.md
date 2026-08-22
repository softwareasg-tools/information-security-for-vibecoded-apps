# Vibesec Auditor: Autonomous AI Security Agent 🛡️

> An autonomous Application Security (AppSec) prompt and skill module for AI coding assistants (Google Antigravity, Cursor, Copilot, Claude).

# Installation

## For Google Antigravity Users

If you are building with AI, you already know how powerful it is to turn ideas into working software.

This skill helps you take the next step: making sure the application you built is safe, reliable, and ready for real users.

You do not need to be a security expert.

Whether you are:

- A founder building your first SaaS product
- A domain expert creating an internal tool
- A designer turning an idea into an app
- A business professional automating your workflow
- A developer experimenting with AI-assisted coding

this skill acts as your security partner.

It reviews your application like an experienced security engineer would, identifies hidden risks, and helps you fix them before they become real problems.

Clone this repository into your global skills folder. Antigravity will automatically detect the `SKILL.md` YAML frontmatter.

```bash
cd ~/.gemini/config/skills
git clone https://github.com/YOUR_USERNAME/vibesec-auditor.git infosec-vibecoded-apps
```

---

## For Cursor / Windsurf Users

AI coding has made it possible for anyone with domain knowledge to build powerful applications.

Add this skill to your project so your AI coding assistant can help you think about security while you build.

Copy the contents of `SKILL.md` into your:

* `.cursor/rules`
* `.windsurfrules`

file at the root of your project.

---

## For ChatGPT / Claude Users

You can use this skill with your AI coding assistant by sharing the contents of `SKILL.md`.

Start with:

> Adopt this security engineer persona. Review my application codebase and help me identify and fix security risks. My codebase is located at [PATH].

The assistant will analyse your application, understand the technology stack automatically, and guide you through improving its security.

---

# What This Skill Does

This is not a generic vulnerability scanner.

It is designed specifically for the new era of AI-assisted development, where people with deep business and domain expertise can build software faster than ever before.

The skill helps answer:

* "Is my app safe before I launch it?"
* "Did my AI coding assistant introduce security problems?"
* "Could users access data they should not see?"
* "Are my APIs and databases protected?"
* "Are my secrets and credentials safe?"
* "What should I fix before going live?"

---

# Security Review Journey

The skill performs a structured review across 12 areas:

1. Repository Security Scan
   Find exposed secrets, risky dependencies, and unsafe configurations.

2. AI-Generated Code Risk Assessment
   Identify common security mistakes introduced during rapid AI-assisted development.

3. Authentication Security Testing
   Review login, sessions, passwords, and identity controls.

4. Authorization Testing
   Verify users can only access what they should.

5. API Security Testing
   Check whether your application's interfaces are protected.

6. Injection Testing
   Look for unsafe inputs and data handling issues.

7. Frontend Security Testing
   Review browser-side risks and exposed information.

8. Database Security Testing
   Check data access controls and database exposure.

9. Cloud Security Testing
   Review hosting, permissions, and cloud configuration.

10. Infrastructure Security
    Check Docker, containers, and deployment setup.

11. Logging and Monitoring
    Ensure problems can be detected and investigated.

12. Security Regression Testing
    Create safeguards so vulnerabilities do not return.

---

# Built for the Vibe Coding Era

Great software has always started with great ideas.

AI has changed who can build software.

Security should not become a barrier to creation.

This skill exists to help builders move from:

> "I built something amazing."

to:

> "I built something amazing that people can safely trust."
