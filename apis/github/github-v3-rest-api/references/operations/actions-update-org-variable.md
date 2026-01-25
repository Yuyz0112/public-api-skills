# PATCH /orgs/{org}/actions/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Update an organization variable**
**Operation ID:** `actions/update-org-variable`

Updates an organization variable that you can reference in a GitHub Actions workflow.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

