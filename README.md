### Senior QA Automation Engineer · SDET

I build test automation platforms that engineering teams actually depend on — from framework architecture and CI/CD integration through to migration strategy, tooling, and the documentation that lets other teams replicate the same work independently.

7+ years across FinTech, banking SaaS, and telecom. I own the test automation architecture on the primary Playwright/TypeScript squad at a risk-management platform serving Tier-1 banks, and give senior support to a second squad's Java/Selenium stack.

**Stack:** Playwright · TypeScript · Cucumber/BDD · Java/Selenium · Pact · Zod · Allure · GitHub Actions · Azure DevOps

Based in Antalya, Türkiye. Open to remote or hybrid SDET / QA automation roles in the EU.

---

**Public repositories here are portfolio work** — production experience lives in private company repos. These projects are built from scratch against public demo apps, with no company code or data, to make architecture decisions, tooling choices, and code quality visible.

---

### Repositories

**[Playwright-cucumber-ai-framework](https://github.com/KKoygun/Playwright-cucumber-ai-framework)**
Playwright + TypeScript + Cucumber BDD with three AI agents (Healer, Planner, Generator) behind a provider-agnostic adapter that supports Groq, Gemini, Claude, OpenAI, or a local Ollama model so page data stays on your network. Groq is verified live and the others are mock-tested. The Healer can retry a broken selector in the same run and logs every attempt; a replayable eval measures it (Groq gpt-oss-120b healed 9/9 broken selectors). Accessibility scans with axe-core; CI on GitHub Actions and Azure Pipelines.

**[playwright-api-framework](https://github.com/KKoygun/playwright-api-framework)**
REST API test framework applying Page Object Model thinking to the HTTP layer — typed client classes, Zod response validation, and Pact consumer-driven contract tests verified against a provider stub. Allure report published to GitHub Pages: [latest report](https://kkoygun.github.io/playwright-api-framework/).

**[defect-bridge](https://github.com/KKoygun/defect-bridge)**
Shows in the Allure report whether a failing test is already tracked in Jira. After every CI run it posts the failure details with screenshots to the linked ticket, flags a regression when a closed ticket's test fails again, adds a "passing again" note when a fix lands, and groups failures in the Allure Categories tab as regression, known defect, or new failure. Jira Cloud (checked against a live site), Data Center and GitHub Issues; runs as a CLI or GitHub Action. Showcase report on GitHub Pages: [latest report](https://kkoygun.github.io/defect-bridge/).

**[TypeDojo](https://github.com/KKoygun/TypeDojo)**
Terminal-based TypeScript training tool — 154 challenges across 19 topics, from language fundamentals to advanced type patterns, with AI-assisted code review built in.
