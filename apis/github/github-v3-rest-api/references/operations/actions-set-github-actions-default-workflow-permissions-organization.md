# PUT /orgs/{org}/actions/permissions/workflow

**Resource:** [actions](../resources/actions.md)
**Set default workflow permissions for an organization**
**Operation ID:** `actions/set-github-actions-default-workflow-permissions-organization`

Sets the default workflow permissions granted to the `GITHUB_TOKEN` when running workflows in an organization, and sets if GitHub Actions
can submit approving pull request reviews. For more information, see
"[Setting the permissions of the GITHUB_TOKEN for your organization](https://docs.github.com/organizations/managing-organization-settings/disabling-or-limiting-github-actions-for-your-organization#setting-the-permissions-of-the-github_token-for-your-organization)."

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

**Schema:** [actions-set-default-workflow-permissions](../schemas/actions-set-default-workflow-permissions/actions-set-default-workflow-permissions.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Success response |

