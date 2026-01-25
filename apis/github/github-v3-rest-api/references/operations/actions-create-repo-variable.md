# POST /repos/{owner}/{repo}/actions/variables

**Resource:** [actions](../resources/actions.md)
**Create a repository variable**
**Operation ID:** `actions/create-repo-variable`

Creates a repository variable that you can reference in a GitHub Actions workflow.

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

