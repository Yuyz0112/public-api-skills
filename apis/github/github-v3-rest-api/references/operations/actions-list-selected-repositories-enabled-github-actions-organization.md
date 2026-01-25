# GET /orgs/{org}/actions/permissions/repositories

**Resource:** [actions](../resources/actions.md)
**List selected repositories enabled for GitHub Actions in an organization**
**Operation ID:** `actions/list-selected-repositories-enabled-github-actions-organization`

Lists the selected repositories that are enabled for GitHub Actions in an organization. To use this endpoint, the organization permission policy for `enabled_repositories` must be configured to `selected`. For more information, see "[Set GitHub Actions permissions for an organization](#set-github-actions-permissions-for-an-organization)."

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

