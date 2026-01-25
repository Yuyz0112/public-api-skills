# dependabot

Endpoints to manage Dependabot.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/enterprises/{enterprise}/dependabot/alerts` | List Dependabot alerts for an enterprise | [View](../operations/dependabot-list-alerts-for-enterprise.md) |
| GET | `/organizations/{org}/dependabot/repository-access` | Lists the repositories Dependabot can access in an organization | [View](../operations/dependabot-repository-access-for-org.md) |
| PATCH | `/organizations/{org}/dependabot/repository-access` | Updates Dependabot's repository access list for an organization | [View](../operations/dependabot-update-repository-access-for-org.md) |
| PUT | `/organizations/{org}/dependabot/repository-access/default-level` | Set the default repository access level for Dependabot | [View](../operations/dependabot-set-repository-access-default-level.md) |
| GET | `/orgs/{org}/dependabot/alerts` | List Dependabot alerts for an organization | [View](../operations/dependabot-list-alerts-for-org.md) |
| GET | `/orgs/{org}/dependabot/secrets` | List organization secrets | [View](../operations/dependabot-list-org-secrets.md) |
| GET | `/orgs/{org}/dependabot/secrets/public-key` | Get an organization public key | [View](../operations/dependabot-get-org-public-key.md) |
| GET | `/orgs/{org}/dependabot/secrets/{secret_name}` | Get an organization secret | [View](../operations/dependabot-get-org-secret.md) |
| PUT | `/orgs/{org}/dependabot/secrets/{secret_name}` | Create or update an organization secret | [View](../operations/dependabot-create-or-update-org-secret.md) |
| DELETE | `/orgs/{org}/dependabot/secrets/{secret_name}` | Delete an organization secret | [View](../operations/dependabot-delete-org-secret.md) |
| GET | `/orgs/{org}/dependabot/secrets/{secret_name}/repositories` | List selected repositories for an organization secret | [View](../operations/dependabot-list-selected-repos-for-org-secret.md) |
| PUT | `/orgs/{org}/dependabot/secrets/{secret_name}/repositories` | Set selected repositories for an organization secret | [View](../operations/dependabot-set-selected-repos-for-org-secret.md) |
| PUT | `/orgs/{org}/dependabot/secrets/{secret_name}/repositories/{repository_id}` | Add selected repository to an organization secret | [View](../operations/dependabot-add-selected-repo-to-org-secret.md) |
| DELETE | `/orgs/{org}/dependabot/secrets/{secret_name}/repositories/{repository_id}` | Remove selected repository from an organization secret | [View](../operations/dependabot-remove-selected-repo-from-org-secret.md) |
| GET | `/repos/{owner}/{repo}/dependabot/alerts` | List Dependabot alerts for a repository | [View](../operations/dependabot-list-alerts-for-repo.md) |
| GET | `/repos/{owner}/{repo}/dependabot/alerts/{alert_number}` | Get a Dependabot alert | [View](../operations/dependabot-get-alert.md) |
| PATCH | `/repos/{owner}/{repo}/dependabot/alerts/{alert_number}` | Update a Dependabot alert | [View](../operations/dependabot-update-alert.md) |
| GET | `/repos/{owner}/{repo}/dependabot/secrets` | List repository secrets | [View](../operations/dependabot-list-repo-secrets.md) |
| GET | `/repos/{owner}/{repo}/dependabot/secrets/public-key` | Get a repository public key | [View](../operations/dependabot-get-repo-public-key.md) |
| GET | `/repos/{owner}/{repo}/dependabot/secrets/{secret_name}` | Get a repository secret | [View](../operations/dependabot-get-repo-secret.md) |
| PUT | `/repos/{owner}/{repo}/dependabot/secrets/{secret_name}` | Create or update a repository secret | [View](../operations/dependabot-create-or-update-repo-secret.md) |
| DELETE | `/repos/{owner}/{repo}/dependabot/secrets/{secret_name}` | Delete a repository secret | [View](../operations/dependabot-delete-repo-secret.md) |
