# POST /repos/{owner}/{repo}/environments/{environment_name}/variables

**Resource:** [actions](../resources/actions.md)
**Create an environment variable**
**Operation ID:** `actions/create-environment-variable`

Create an environment variable that you can reference in a GitHub Actions workflow.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

