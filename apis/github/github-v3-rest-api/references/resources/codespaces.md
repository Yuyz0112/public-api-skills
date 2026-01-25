# codespaces

Endpoints to manage Codespaces using the REST API.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/codespaces` | List codespaces for the organization | [View](../operations/codespaces-list-in-organization.md) |
| PUT | `/orgs/{org}/codespaces/access` | Manage access control for organization codespaces | [View](../operations/codespaces-set-codespaces-access.md) |
| POST | `/orgs/{org}/codespaces/access/selected_users` | Add users to Codespaces access for an organization | [View](../operations/codespaces-set-codespaces-access-users.md) |
| DELETE | `/orgs/{org}/codespaces/access/selected_users` | Remove users from Codespaces access for an organization | [View](../operations/codespaces-delete-codespaces-access-users.md) |
| GET | `/orgs/{org}/codespaces/secrets` | List organization secrets | [View](../operations/codespaces-list-org-secrets.md) |
| GET | `/orgs/{org}/codespaces/secrets/public-key` | Get an organization public key | [View](../operations/codespaces-get-org-public-key.md) |
| GET | `/orgs/{org}/codespaces/secrets/{secret_name}` | Get an organization secret | [View](../operations/codespaces-get-org-secret.md) |
| PUT | `/orgs/{org}/codespaces/secrets/{secret_name}` | Create or update an organization secret | [View](../operations/codespaces-create-or-update-org-secret.md) |
| DELETE | `/orgs/{org}/codespaces/secrets/{secret_name}` | Delete an organization secret | [View](../operations/codespaces-delete-org-secret.md) |
| GET | `/orgs/{org}/codespaces/secrets/{secret_name}/repositories` | List selected repositories for an organization secret | [View](../operations/codespaces-list-selected-repos-for-org-secret.md) |
| PUT | `/orgs/{org}/codespaces/secrets/{secret_name}/repositories` | Set selected repositories for an organization secret | [View](../operations/codespaces-set-selected-repos-for-org-secret.md) |
| PUT | `/orgs/{org}/codespaces/secrets/{secret_name}/repositories/{repository_id}` | Add selected repository to an organization secret | [View](../operations/codespaces-add-selected-repo-to-org-secret.md) |
| DELETE | `/orgs/{org}/codespaces/secrets/{secret_name}/repositories/{repository_id}` | Remove selected repository from an organization secret | [View](../operations/codespaces-remove-selected-repo-from-org-secret.md) |
| GET | `/orgs/{org}/members/{username}/codespaces` | List codespaces for a user in organization | [View](../operations/codespaces-get-codespaces-for-user-in-org.md) |
| DELETE | `/orgs/{org}/members/{username}/codespaces/{codespace_name}` | Delete a codespace from the organization | [View](../operations/codespaces-delete-from-organization.md) |
| POST | `/orgs/{org}/members/{username}/codespaces/{codespace_name}/stop` | Stop a codespace for an organization user | [View](../operations/codespaces-stop-in-organization.md) |
| GET | `/repos/{owner}/{repo}/codespaces` | List codespaces in a repository for the authenticated user | [View](../operations/codespaces-list-in-repository-for-authenticated-user.md) |
| POST | `/repos/{owner}/{repo}/codespaces` | Create a codespace in a repository | [View](../operations/codespaces-create-with-repo-for-authenticated-user.md) |
| GET | `/repos/{owner}/{repo}/codespaces/devcontainers` | List devcontainer configurations in a repository for the authenticated user | [View](../operations/codespaces-list-devcontainers-in-repository-for-authenticated-user.md) |
| GET | `/repos/{owner}/{repo}/codespaces/machines` | List available machine types for a repository | [View](../operations/codespaces-repo-machines-for-authenticated-user.md) |
| GET | `/repos/{owner}/{repo}/codespaces/new` | Get default attributes for a codespace | [View](../operations/codespaces-pre-flight-with-repo-for-authenticated-user.md) |
| GET | `/repos/{owner}/{repo}/codespaces/permissions_check` | Check if permissions defined by a devcontainer have been accepted by the authenticated user | [View](../operations/codespaces-check-permissions-for-devcontainer.md) |
| GET | `/repos/{owner}/{repo}/codespaces/secrets` | List repository secrets | [View](../operations/codespaces-list-repo-secrets.md) |
| GET | `/repos/{owner}/{repo}/codespaces/secrets/public-key` | Get a repository public key | [View](../operations/codespaces-get-repo-public-key.md) |
| GET | `/repos/{owner}/{repo}/codespaces/secrets/{secret_name}` | Get a repository secret | [View](../operations/codespaces-get-repo-secret.md) |
| PUT | `/repos/{owner}/{repo}/codespaces/secrets/{secret_name}` | Create or update a repository secret | [View](../operations/codespaces-create-or-update-repo-secret.md) |
| DELETE | `/repos/{owner}/{repo}/codespaces/secrets/{secret_name}` | Delete a repository secret | [View](../operations/codespaces-delete-repo-secret.md) |
| POST | `/repos/{owner}/{repo}/pulls/{pull_number}/codespaces` | Create a codespace from a pull request | [View](../operations/codespaces-create-with-pr-for-authenticated-user.md) |
| GET | `/user/codespaces` | List codespaces for the authenticated user | [View](../operations/codespaces-list-for-authenticated-user.md) |
| POST | `/user/codespaces` | Create a codespace for the authenticated user | [View](../operations/codespaces-create-for-authenticated-user.md) |
| GET | `/user/codespaces/secrets` | List secrets for the authenticated user | [View](../operations/codespaces-list-secrets-for-authenticated-user.md) |
| GET | `/user/codespaces/secrets/public-key` | Get public key for the authenticated user | [View](../operations/codespaces-get-public-key-for-authenticated-user.md) |
| GET | `/user/codespaces/secrets/{secret_name}` | Get a secret for the authenticated user | [View](../operations/codespaces-get-secret-for-authenticated-user.md) |
| PUT | `/user/codespaces/secrets/{secret_name}` | Create or update a secret for the authenticated user | [View](../operations/codespaces-create-or-update-secret-for-authenticated-user.md) |
| DELETE | `/user/codespaces/secrets/{secret_name}` | Delete a secret for the authenticated user | [View](../operations/codespaces-delete-secret-for-authenticated-user.md) |
| GET | `/user/codespaces/secrets/{secret_name}/repositories` | List selected repositories for a user secret | [View](../operations/codespaces-list-repositories-for-secret-for-authenticated-user.md) |
| PUT | `/user/codespaces/secrets/{secret_name}/repositories` | Set selected repositories for a user secret | [View](../operations/codespaces-set-repositories-for-secret-for-authenticated-user.md) |
| PUT | `/user/codespaces/secrets/{secret_name}/repositories/{repository_id}` | Add a selected repository to a user secret | [View](../operations/codespaces-add-repository-for-secret-for-authenticated-user.md) |
| DELETE | `/user/codespaces/secrets/{secret_name}/repositories/{repository_id}` | Remove a selected repository from a user secret | [View](../operations/codespaces-remove-repository-for-secret-for-authenticated-user.md) |
| GET | `/user/codespaces/{codespace_name}` | Get a codespace for the authenticated user | [View](../operations/codespaces-get-for-authenticated-user.md) |
| DELETE | `/user/codespaces/{codespace_name}` | Delete a codespace for the authenticated user | [View](../operations/codespaces-delete-for-authenticated-user.md) |
| PATCH | `/user/codespaces/{codespace_name}` | Update a codespace for the authenticated user | [View](../operations/codespaces-update-for-authenticated-user.md) |
| POST | `/user/codespaces/{codespace_name}/exports` | Export a codespace for the authenticated user | [View](../operations/codespaces-export-for-authenticated-user.md) |
| GET | `/user/codespaces/{codespace_name}/exports/{export_id}` | Get details about a codespace export | [View](../operations/codespaces-get-export-details-for-authenticated-user.md) |
| GET | `/user/codespaces/{codespace_name}/machines` | List machine types for a codespace | [View](../operations/codespaces-codespace-machines-for-authenticated-user.md) |
| POST | `/user/codespaces/{codespace_name}/publish` | Create a repository from an unpublished codespace | [View](../operations/codespaces-publish-for-authenticated-user.md) |
| POST | `/user/codespaces/{codespace_name}/start` | Start a codespace for the authenticated user | [View](../operations/codespaces-start-for-authenticated-user.md) |
| POST | `/user/codespaces/{codespace_name}/stop` | Stop a codespace for the authenticated user | [View](../operations/codespaces-stop-for-authenticated-user.md) |
