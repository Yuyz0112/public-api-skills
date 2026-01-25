# GET /orgs/{org}/actions/permissions

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions permissions for an organization**
**Operation ID:** `actions/get-github-actions-permissions-organization`

Gets the GitHub Actions permissions policy for repositories and allowed actions and reusable workflows in an organization.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-organization-permissions](../schemas/actions-organization-permissions/actions-organization-permissions.md)

