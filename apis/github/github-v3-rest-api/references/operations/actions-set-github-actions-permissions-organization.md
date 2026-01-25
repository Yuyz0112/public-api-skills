# PUT /orgs/{org}/actions/permissions

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions permissions for an organization**
**Operation ID:** `actions/set-github-actions-permissions-organization`

Sets the GitHub Actions permissions policy for repositories and allowed actions and reusable workflows in an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

