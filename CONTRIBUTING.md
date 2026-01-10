# Contributing to Navadrishti

Thank you for your interest in contributing to **Navadrishti (नवदृष्टि)**.  
Navadrishti is an **AI-powered operating system for social impact**, built to support NGOs, CSR teams, and individuals at scale.

We welcome contributors who believe in building **production-grade, ethical, and impactful software**.

---

## About Navadrishti

Navadrishti is **not a volunteering platform**.  
It is an **operations and intelligence platform** for the social sector, combining:

- NGO operations management
- CSR campaign automation
- AI-driven impact reporting
- Skill-based service exchange
- Verified social impact profiles

Every contribution must align with **trust, transparency, and real-world usability**.

---

## Repository and branching strategy

We follow a controlled Git workflow:

- `main` – Production branch (live deployments)
- `develop` – Active development branch
- `feature/*` – New features
- `fix/*` – Bug fixes
- `docs/*` – Documentation changes

**Direct pushes to `main` are not allowed.**

---

## Contribution workflow

### 1. Clone the repository

```bash
git clone https://github.com/navadrishti/<repo-name>.git
cd <repo-name>
```

### 2. Create a feature branch

```bash
git checkout develop
git pull origin develop
git checkout -b feature/<short-description>
```

---

## Development guidelines

### Code quality
- **Clean code:** Write clean, readable, and modular code
- **Consistency:** Follow existing architecture and patterns
- **Minimalism:** Avoid unnecessary dependencies
- **Secrets:** Do not commit secrets, tokens, or credentials

### Security
- **.env:** Never commit `.env` files
- **Config:** Use environment variables for configuration
- **Access:** Respect role-based access control (RBAC)

### AI and ML contributions
- **Clarity:** Clearly document models and assumptions
- **Explainability:** Prefer explainable and auditable logic
- **Justification:** Avoid black-box AI without justification
- **Ethics:** Respect data privacy and ethical AI practices

---

## Commit message convention

Use clear, meaningful commit messages:
- `feat: add CSR campaign generator`
- `fix: resolve JWT expiry issue`
- `docs: update contributing guidelines`
- `refactor: optimize API response flow`

Avoid vague messages like:
- `update`
- `final`
- `fix issue`

---

## Pull request process

### Push your branch

```bash
git push origin feature/<branch-name>
```

### Open a pull request targeting develop

Include:
- **What:** What was changed
- **Why:** Why it was changed
- **UI proof:** Screenshots/videos (for UI changes)
- **Links:** Linked issues (if applicable)

All PRs are reviewed by core maintainers.

### Reviews and merging
- **Review required:** PRs must be reviewed before merging
- **Feedback loop:** Feedback may be requested
- **Protected branches:** Only maintainers can merge into:
  - `develop`
  - `main` (production)

Production merges are handled by the core team.

---

## Documentation contributions

Documentation is highly encouraged. You can contribute to:
- README updates
- Architecture documentation
- API references
- CSR and AI workflow explanations

Use `docs/` or `docs/*` branches.

---

## Testing expectations

Before submitting a PR:
- **Critical flows:** Test critical flows
- **UI:** Verify UI responsiveness
- **API:** Validate API responses
- **AI:** Document expected AI behavior

Automated tests will be expanded over time.

---

## Legal and ethical guidelines

By contributing, you agree that:
- **Production use:** Your code may be used in production
- **Licensing:** No plagiarized or unlicensed code is allowed
- **Data:** Sensitive social data must be handled responsibly
- **Ethics:** Contributions must align with ethical AI usage

---

## Code of conduct

We expect:
- **Respectful communication**
- **Inclusive collaboration**
- **Constructive feedback**
- **Professional behavior**

Harassment, misuse of access, or unethical behavior will result in removal.

---

## Getting help

If you are unsure about anything:
- **Open an Issue**
- **Start a Discussion**
- Reach out to the core team: **contactus.navdrishti@gmail.com**

---

## Closing note

Navadrishti is building **core infrastructure for social impact in India**.  
Every contribution matters — but **quality, responsibility, and trust matter more**.

Thank you for being part of this journey.
