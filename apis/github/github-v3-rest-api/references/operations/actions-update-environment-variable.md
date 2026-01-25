# PATCH /repos/{owner}/{repo}/environments/{environment_name}/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Update an environment variable**
**Operation ID:** `actions/update-environment-variable`

Updates an environment variable that you can reference in a GitHub Actions workflow.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

