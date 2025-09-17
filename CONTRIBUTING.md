# Contributing to DSRT.js

Thank you for your interest in contributing to DSRT.js! By participating, you agree to follow our [Code of Conduct](./CODE_OF_CONDUCT.md) and contribute in a professional and constructive manner.

---

## 1️⃣ Getting Started

1. **Fork the repository**  
2. **Clone your fork locally**
```bash
git clone https://github.com/your-username/dsrt-nextjs.git
cd dsrt-nextjs

3. Create a new branch for your feature or bugfix



git checkout -b feature/my-feature

4. Install dependencies



npm install
# or
yarn install


---

2️⃣ Making Changes

Follow coding standards (see section 3)

Add meaningful comments for complex logic

Update docs / examples if your changes affect API or visuals

Test your changes locally before committing



---

3️⃣ Coding Standards

Language & Syntax: ES6+ JavaScript / TypeScript

Indentation: 2 spaces

Variables: camelCase

Constants: UPPER_CASE

Functions: descriptive, clear names

Comments: explain non-trivial logic

Files: organize according to folder structure (pages/, components/, public/, docs/, tests/)



---

4️⃣ Issue Reporting

Before opening a new issue:

Check if the issue already exists

Use the template in .github/ISSUE_TEMPLATE.md


Provide:

Steps to reproduce

Expected behavior

Actual behavior

Browser / OS / Device info

Screenshots / GIFs if relevant


Label your issue (bug, enhancement, question)


---

5️⃣ Pull Request (PR) Guidelines

PR target: develop or main (see repo policy)

Must pass CI, lint, and tests

Include description of changes

Reference any related issues

Include screenshots / demo links if UI affected

Keep PR small and focused

At least 1 reviewer approval required before merge



---

6️⃣ Branching Strategy

main → Stable release only

develop → Latest development / integration

Feature branches → feature/xyz

Bugfix branches → bugfix/abc

Hotfix branches → hotfix/urgent-fix


Merge feature branches → develop, then develop → main for release


---

7️⃣ Testing

Write unit tests for DSRT.js core features

Test Next.js integration for pages/components using DSRT.js

Optional: include interactive example tests (canvas rendering)

Run tests locally before pushing:


npm test
# or
yarn test


---

8️⃣ Security

Report security vulnerabilities via private channel first (see SECURITY.md)

Do not include secrets / API keys in commits

Avoid using untrusted third-party code without approval



---

9️⃣ Documentation

Update /docs for any API changes

Include examples / screenshots if needed

Ensure tutorials & usage guides remain accurate



---

🔟 Communication & Etiquette

Follow Code of Conduct

Provide constructive, respectful feedback

Collaborate in a professional manner

Be patient and clear in discussions



---

11️⃣ Additional Notes

Keep commits atomic & descriptive

Rebase / squash when appropriate to maintain clean history

Celebrate merged PRs and acknowledge contributors
