# DELETE /orgs/{org}/actions/permissions/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Disable a selected repository for GitHub Actions in an organization**
**Operation ID:** `actions/disable-selected-repository-github-actions-organization`

Removes a repository from the list of selected repositories that are enabled for GitHub Actions in an organization. To use this endpoint, the organization permission policy for `enabled_repositories` must be configured to `selected`. For more information, see "[Set GitHub Actions permissions for an organization](#set-github-actions-permissions-for-an-organization)."

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

