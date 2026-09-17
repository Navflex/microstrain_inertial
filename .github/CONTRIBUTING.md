# Contributing to Navflex (Internal)

Thank you for contributing to **Navflex**! This repository is intended for **internal use only**. All contributions should follow our internal engineering standards and workflows.

---

## 📌 Scope

This repository is **not open to the public**. Contributions are limited to Navflex team members and approved contractors. Please do not share or distribute any content externally.

---

## 🛠️ Internal Contribution Guidelines

### 🔍 Before You Start

- Review relevant documentation on our [Development Workflow](https://navflex.atlassian.net/wiki/spaces/NDT/pages/305758257/Development+Workflow).
- Confirm with the feature owner or [tech lead](https://navflex.atlassian.net/wiki/spaces/NDT/pages/247922704/Sub-Teams#Sub-Teams) before starting significant work.

### 🐛 Reporting Issues / Proposing Enhancements

- Use **[ClickUp](https://app.clickup.com/)** to report bugs or request features.
- Make sure [tickets](https://navflex.atlassian.net/wiki/spaces/NDT/pages/277315627/Ticket+Definition) are well-labeled and assigned to the correct team.
- Include logs, screenshots, or clear reproduction steps when applicable.
- For larger changes, raise the topic during an engineering sync or in `#eng-software`.

---

## 🔁 Development Workflow

1. **[Branching](https://navflex.atlassian.net/wiki/spaces/NDT/pages/305758257/Development+Workflow#Branching)**

    - Create branches from `develop (or main)` using this format:
      `feature/<ticket-id>-<short-description>`
      Example:
      `feature/CU-86c4kyx5a-add-auth-logging`

2. **[Coding Standards](https://navflex.atlassian.net/wiki/spaces/NKB/pages/164692057/Coding+Standards)**

    - Keep code modular, documented, and testable.

3. **[Commits](https://navflex.atlassian.net/wiki/spaces/NDT/pages/305758257/Development+Workflow#ClickUp-Integration)**

    - Use clear, descriptive commit messages.
    - Reference ClickUp tickets (e.g., `CU-86c4kyx5a: Add auth logging hook`).

4. **[Testing](https://navflex.atlassian.net/wiki/spaces/NDT/pages/189333540/Dev+Testing?atlOrigin=eyJpIjoiODNlZGMzYWI0NmJkNDYxNzlkMjI0MDQzOGI3MGNmZTgiLCJwIjoiY29uZmx1ZW5jZS1jaGF0cy1pbnQifQ)**

    - Run unit and integration tests.
    - Ensure the CI pipeline passes.
    - Write new tests for new functionality.

5. **[Pull Requests](https://navflex.atlassian.net/wiki/spaces/NDT/pages/189333550/PR+Process?atlOrigin=eyJpIjoiMjY3ZTg5Njg3ZDhkNGMwYWEyNjRmZjk0MmFlY2I0YzMiLCJwIjoiY29uZmx1ZW5jZS1jaGF0cy1pbnQifQ)**

    - Open a PR to the `develop (or main)` branch.
    - Include a link to the related ClickUp ticket.
    - Provide a clear summary of the changes.
    - Request reviewers as needed.
    - Address review comments promptly.

6. **[Merging](https://navflex.atlassian.net/wiki/spaces/NDT/pages/189333550/PR+Process#Merging)**

    - Only codeowners or designated maintainers may merge to `develop`.
    - All CI checks must pass before merging.

---

## 🙋 Questions?

- Post in `#eng-software` on Slack.
- Mention the relevant tech lead or maintainer.
- Or comment directly on the ClickUp ticket.

---

Thank you for helping make **Navflex** better! 🚀
