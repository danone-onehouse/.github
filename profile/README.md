## Welcome to Danone OneHouse

The Data & Analytics platform powering Danone's digital transformation.

---

### Quick Links

- [GitHub Organization](https://github.com/danone-onehouse) — This page
- [GitHub Status](https://www.githubstatus.com/) — Service health & incidents
- [Documentation Wiki](https://github.com/danone/danone.documentation/wiki/) — Danone-wide GitHub guides & policies
- [Microsoft Learn — GitHub Skills](https://learn.microsoft.com/en-gb/collections/kkqrhmxoqn54) — Self-paced GitHub training

---

### Users & Team Management

- [Quick User guide](https://danone.sharepoint.com/sites/DMS-WWOneSource/MainLibrary/Forms/AllItems.aspx?id=%2Fsites%2FDMS%2DWWOneSource%2FMainLibrary%2FOneHouse%2FHow%20to%20request%20access%20to%20GitHub%2Epdf&parent=%2Fsites%2FDMS%2DWWOneSource%2FMainLibrary%2FOneHouse) for GitHub access and Copilot in Danone-Onehouse
- **Teams & members** — View current structure at [GitHub Teams](https://github.com/orgs/danone-onehouse/teams)
- **Repository permissions** — Access is managed through EntraId and Idp GitHub Teams. Each repo has dedicated teams with read, write, or admin roles.

---

### Working in GitHub — Best Practices

See also: [Work in GitHub](https://github.com/danone/danone.documentation/wiki/Work-in-GitHub) (Danone wiki)

| Topic | Guidance |
|-------|----------|
| **Branching** | Trunk-based development. Short-lived feature branches, merge frequently. |
| **Pull Requests** | Keep PRs small and focused. Use the PR template and JIRA Id in the PR title. Require at least one review before merge. |
| **Commits** | Write meaningful commit messages. Reference Jira ticket IDs (e.g., `[O20-1234]`). |
| **CI/CD** | All PRs must pass linting, SAST scanning (Checkmarx), and relevant build checks before merge. |
| **Security** | Secrets must never be committed. Use Azure Key Vault + GitHub Secrets. Enable Dependabot/Renovate alerts. |

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

- Do you need help? Follow the useful resources available via [Support](https://danone.sharepoint.com/sites/DMS-WWOneSource/SitePages/Operations-%26-Support.aspx#incidents-support)

