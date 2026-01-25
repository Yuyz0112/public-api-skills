# PUT /repos/{owner}/{repo}/actions/permissions

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions permissions for a repository**
**Operation ID:** `actions/set-github-actions-permissions-repository`

Sets the GitHub Actions permissions policy for enabling GitHub Actions and allowed actions and reusable workflows in the repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

