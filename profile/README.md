## Welcome to Danone OneHouse

The Data & Analytics platform powering Danone's digital transformation.

---

### Quick Links

- [GitHub Copilot Requests](https://danone.service-now.com/danone_it?id=sc_cat_item_it&sys_id=1fd23593eb876690f8a5f30e8ad0cd9b) — Request Copilot access
- [GitHub Organization](https://github.com/danone-onehouse) — This page
- [GitHub Status](https://www.githubstatus.com/) — Service health & incidents
- [Documentation Wiki](https://github.com/danone/danone.documentation/wiki/) — Danone-wide GitHub guides & policies
- [Microsoft Learn — GitHub Skills](https://learn.microsoft.com/en-gb/collections/kkqrhmxoqn54) — Self-paced GitHub training

---

### Users & Team Management

- **Join the organization** — Request access via your team lead or raise a ticket in [ServiceNow](https://danone.service-now.com/timesheetnow?id=sc_cat_item_it&sys_id=2adc9e2c1ba5ba1002815205604bcb0a&sysparm_category=fb645335eb7392d0f8a5f30e8ad0cd77)
- **Teams & members** — View current structure at [GitHub Teams](https://github.com/orgs/danone-onehouse/teams)
- **Repository permissions** — Access is managed through EntraId and Idp GitHub Teams. Each repo has dedicated teams with read, write, or admin roles.

---

### Working in GitHub — Best Practices

See also: [Work in GitHub](https://github.com/danone/danone.documentation/wiki/Work-in-GitHub) (Danone wiki)

| Topic | Guidance |
|-------|----------|
| **Branching** | Trunk-based development. Short-lived feature branches, merge frequently. |
| **Pull Requests** | Keep PRs small and focused. Use the PR template. Require at least one review before merge. |
| **Commits** | Write meaningful commit messages. Reference Jira ticket IDs (e.g., `[O20-1234]`). |
| **CI/CD** | All PRs must pass linting, SAST scanning (Checkmarx), and relevant build checks before merge. |
| **Security** | Secrets must never be committed. Use Azure Key Vault + GitHub Secrets. Enable Dependabot alerts. |

---

### Training & Learning

- [Microsoft Learn — GitHub Skills Challenge](https://learn.microsoft.com/en-gb/collections/kkqrhmxoqn54) — Official Microsoft GitHub training path
- [Danone Documentation Wiki](https://github.com/danone/danone.documentation/wiki/) — Organization-wide guides

---

### Platform Repositories

| Area | Repositories |
|------|-------------|
| **Infrastructure** | `platform-infrastructure`, `management-infrastructure` |
| **DTU Management** | `dtu-infrastructure`, `dtu-management` |
| **Ingestion** | `ingestion-adf`, `ingestion-databricks`, `ingestion-sql`, `ingestion-config-app` |
| **Data Quality** | `dq-observability` |
| **Shared Tooling** | `shared`, `house-tools`, `transformations-library` |
| **Release** | `release`, `backup-data` |
| **QA** | `test-automation` |
| **AI / ML** | `ai-dlc` |

---

### Support

- Questions? Reach the OneHouse platform team via [Palina SULKOUSKAYA](mailto:Palina.SULKOUSKAYA@external.danone.com)
- Platform issues or requests? Raise a ticket in [ServiceNow](https://danone.service-now.com/danone_it?id=search&spa=1&q=onehouse)
