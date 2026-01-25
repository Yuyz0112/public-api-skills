# POST /orgs/{org}/actions/variables

**Resource:** [actions](../resources/actions.md)
**Create an organization variable**
**Operation ID:** `actions/create-org-variable`

Creates an organization variable that you can reference in a GitHub Actions workflow.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response when creating a variable |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

