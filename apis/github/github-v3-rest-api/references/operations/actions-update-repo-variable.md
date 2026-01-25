# PATCH /repos/{owner}/{repo}/actions/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Update a repository variable**
**Operation ID:** `actions/update-repo-variable`

Updates a repository variable that you can reference in a GitHub Actions workflow.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

