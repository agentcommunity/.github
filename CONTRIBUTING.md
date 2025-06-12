# Contributing to Agent Community 🌐

Thank you for your interest in contributing to **agentcommunity**! This guide applies to all our repositories and helps keep collaboration consistent, inclusive, and effective across diverse work‑items.

---

## 🗣️ Opening Issues & Discussions

### 1. 🐛 Bug reports and actionable items

* Post an **issue** in the relevant repository (e.g. `agentservicediscovery`)
* Choose the correct labels (`bug`, `spec`, `implementation`)

### 2. 💡 Design or proposal discussions

* Use **repository Discussions** if tightly scoped to that project
* Use **organization-level Discussions** for broad or cross‑repo topics (governance, new features, etc.)

> **Before posting**: search existing issues/discussions to avoid duplicates ([arxiv.org][2])

---

## 🤝 Pull Requests

We value your contributions! Please follow these courtesies when submitting:

1. **Fork** the repository and create a branch (`feature/…`, `fix/…`)
2. **Adhere to style** and patterns already in place
3. **Write tests** for new or changed behavior
4. **Update documentation**, examples, and READMEs as needed
5. **Link related issues or discussions** in your PR
6. **Request review** from project maintainers or assign via CODEOWNERS

---

## ✅ Development Guidelines

### Code Quality

* Follow existing patterns & code style
* Validate inputs, handle errors clearly
* Keep changes scope-limited and atomic, improving reviewability

### Documentation

* Keep READMEs accurate & up-to-date
* Document any configuration, examples, or usage scenarios
* Use inline code comments when behavior isn't obvious

### Security

* Validate all untrusted inputs
* Consider authentication, authz, and auditability
* If introducing new security considerations, mention them in SECURITY.md in `.github`

---

## 🚀 Getting Started Locally

```bash
git clone https://github.com/agentcommunity/<repo>.git
cd <repo>
git checkout -b feature/your-change
# Make changes…
git commit -m "Short, descriptive message"
git push origin feature/your-change
# Navigate to GitHub and open a PR
```

---

## 🧭 Issues Template & Labels

Each repo includes issue and PR templates to help you format your contributions. Common labels include:

* `kind/spec`, `kind/implementation`, `help-wanted`, `good-first-issue`

---

## 🛡️ Code of Conduct

Adhering to our **Code of Conduct** is required when participating in any repo, issue, PR, or discussion. Please review our shared policy in `.github/CODE_OF_CONDUCT.md`.

---

## 📄 License

Your contributions are licensed under the **MIT License**, consistent with the rest of agentcommunity.

---

## 💬 Quick Community FAQ

**Q: Where should I ask general questions or brainstorm?**
A: Use **organization Discussions**, organized by categories like “Governance” and “Work‑Item Proposals.” Repository-level Discussions are for implementation-specific Qs.

**Q: Can I propose a new work‑item?**
A: Yes! Start in the org-level Discussions using the `WORK-ITEM_TEMPLATE.md` in `.meta`.

**Q: Do I need to sign a CLA or DCO?**
A: Yes — we require a signed commit (via `Signed-off-by`) or minor CLA acknowledgement. Our `.github` repo contains all necessary templates and automation.

---

Thanks for building agents with us — happy contributing!
