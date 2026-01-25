# GET /orgs/{org}/actions/permissions/workflow

**Resource:** [actions](../resources/actions.md)
**Get default workflow permissions for an organization**
**Operation ID:** `actions/get-github-actions-default-workflow-permissions-organization`

Gets the default workflow permissions granted to the `GITHUB_TOKEN` when running workflows in an organization,
as well as whether GitHub Actions can submit approving pull request reviews. For more information, see
"[Setting the permissions of the GITHUB_TOKEN for your organization](https://docs.github.com/organizations/managing-organization-settings/disabling-or-limiting-github-actions-for-your-organization#setting-the-permissions-of-the-github_token-for-your-organization)."

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-get-default-workflow-permissions](../schemas/actions-get-default-workflow-permissions/actions-get-default-workflow-permissions.md)

