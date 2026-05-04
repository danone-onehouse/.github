## Welcome to Danone OneHouse

The Data & Analytics platform powering Danone's digital transformation.

---

### Quick Links

- [GitHub Copilot Requests](https://github.com/organizations/danone-onehouse/settings/copilot) — Request Copilot access
- [GitHub Organization](https://github.com/danone-onehouse) — This page
- [GitHub Status](https://www.githubstatus.com/) — Service health & incidents

---

### Users & Team Management

- **Join the organization** — Request access via your team lead or raise a ticket in [ServiceNow / Jira link]
- **Teams & members** — View current structure at [GitHub Teams](https://github.com/orgs/danone-onehouse/teams)
- **Repository permissions** — Access is managed through GitHub Teams. Each repo has dedicated teams with read, write, or admin roles.

---

### Working in GitHub — Best Practices

| Topic | Guidance |
|-------|----------|
| **Branching** | Trunk-based development. Short-lived feature branches, merge frequently. |
| **Pull Requests** | Keep PRs small and focused. Use the PR template. Require at least one review before merge. |
| **Commits** | Write meaningful commit messages. Reference Jira ticket IDs (e.g., `[O20-1234]`). |
| **CI/CD** | All PRs must pass linting, SAST scanning (Checkmarx), and relevant build checks before merge. |
| **Security** | Secrets must never be committed. Use Azure Key Vault + GitHub Secrets. Enable Dependabot alerts. |

---

### Platform Repositories

| Area | Repositories |
|------|-------------|
| **Infrastructure** | `platform-infrastructure`, `management-infrastructure` |
| **DTU Management** | `dtu-infrastructure`, `dtu-management` |
| **Ingestion** | `ingestion-adf`, `ingestion-databricks`, `ingestion-sql`, `ingestion-configuration` |
| **Data Quality** | `dq-observability` |
| **Shared Tooling** | `shared`, `house-tools`, `transformations-library` |
| **Release** | `release`, `backup-data` |
| **QA** | `test-automation` |
| **AI / ML** | `ai-dlc` |

---

### Support

- Questions? Reach the OneHouse platform team via [Slack / Teams channel link]
- Platform issues or requests? Raise a ticket in [ServiceNow / Jira link]
