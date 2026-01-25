# GET /repos/{owner}/{repo}/actions/permissions

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions permissions for a repository**
**Operation ID:** `actions/get-github-actions-permissions-repository`

Gets the GitHub Actions permissions policy for a repository, including whether GitHub Actions is enabled and the actions and reusable workflows allowed to run in the repository.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-repository-permissions](../schemas/actions-repository-permissions/actions-repository-permissions.md)

