# Rahul Shukla — Senior SDET & QA Automation Architect

> **I build test automation systems that reason about correctness — not just check exact values.**  
> 10+ years in QA. Now integrating LLMs into automation frameworks to solve problems that brittle assertions can't.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rahul--shukla--qa-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/rahul-shukla-qa)
[![Portfolio](https://img.shields.io/badge/Portfolio-rahulshukla.info-000000?style=flat&logo=safari)](https://rahulshukla.info)
[![X](https://img.shields.io/badge/X-@qarahulshukla-000000?style=flat&logo=x)](https://x.com/qarahulshukla)

---

## What I Actually Build

Most automation engineers write tests. I build the infrastructure underneath — frameworks that are maintainable at scale, CI pipelines that don't flake in production, and increasingly, systems that use LLMs to validate what "correct" actually means for a given API response.

Three things I'm focused on right now:

- **LLM-based semantic validation** — replacing brittle exact-value assertions with AI reasoning that understands intent
- **Flaky test elimination** — locator strategy, async handling, and test isolation done properly
- **AI-augmented QA infrastructure** — self-healing locators, intelligent failure triage, LLM-assisted test generation

---

## 🔥 Featured Project: AI-Powered Test Automation Framework

**[→ View Repository](https://github.com/Shukla0312/ai-powered-test-automation)**

The core problem: traditional assertions fail the moment a value changes by one character, even if the response is semantically correct. This framework replaces that with LLM-based reasoning.

**How it works:**
- Sends API response + validation intent to an LLM
- Gets back: PASS/FAIL verdict + natural language reasoning + confidence score
- Falls back gracefully to schema validation when AI is unavailable

**What's inside:**
| Component | What it does |
|---|---|
| `validator/` | LLM-based semantic validation engine |
| `decision-engine/` | Combines AI verdict + schema result into final outcome |
| `services/` | API clients for ReqRes, REST Countries |
| `config/` | Toggle between mock AI and real LLM calls |

**Key features:**
- 🧠 AI verdict with reasoning + confidence score per test
- 🔁 Retry logic, response caching, rate-limit handling
- ⚙️ Config-driven: run in mock mode without API keys
- 🧩 Modular — swap the LLM provider without touching test logic
- 📊 Validated against real-world APIs (ReqRes, REST Countries)

> *Traditional automation checks exact values. This framework validates correctness intelligently — understanding what a response should mean, not just what it should equal.*

---

## 🛠️ Full Tech Stack

**Test Automation**
`Cypress` `Playwright` `Selenium` `WebdriverIO`

**Languages**
`JavaScript` `TypeScript` `Java`

**API & Performance**
`REST Assured` `Postman` `Newman` `JMeter`

**BDD & Reporting**
`Cucumber/Gherkin` `Allure` `Mochawesome`

**CI/CD & DevOps**
`GitHub Actions` `Jenkins` `Docker`

**AI / LLM Integration**
`OpenAI API` `Claude API` `LangChain` `Semantic Validation`

**Domain Experience**
`Fintech` `Telecom` `Insurance` `SaaS`

---

## 📊 GitHub Stats

![Rahul's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Shukla0312&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shukla0312&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff)

---

## 🏆 Work Record

| Metric | Value |
|---|---|
| Experience | 10+ years |
| Longest Engagement | 3+ years / 3,800+ hours (SaaS product, sole automation engineer) |
| Frameworks Built | Multiple from scratch across fintech, telecom, insurance & SaaS |
| Domains | Fintech · Telecom · Insurance · SaaS |

---

## 📈 Current Focus (2025–26)

- Building production-grade LLM validation layers for API test suites
- Self-healing locator strategies using AI-assisted element resolution
- Integrating LLM-based failure triage into CI/CD pipelines
- Exploring RAG-based test knowledge bases for large codebases

---

## 🎯 Open To

Remote-first roles with **Series A–C product teams** moving fast:

- Senior SDET / QA Automation Architect
- AI + Testing focused engineering roles
- Freelance / contract engagements (available now)

Timezone: IST (UTC+5:30) — overlap-friendly with EU mornings and US afternoons.

---

## 📫 Let's Connect

| | |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/rahul-shukla-qa](https://www.linkedin.com/in/rahul-shukla-qa) |
| 🌐 Portfolio | [rahulshukla.info](https://rahulshukla.info) |
| 🐦 X / Twitter | [@qarahulshukla](https://x.com/qarahulshukla) |

---

> *The future of testing isn't writing more assertions —*  
> *it's building systems intelligent enough to understand what correct actually means.*
