# GET /orgs/{org}/actions/variables/{name}

**Resource:** [actions](../resources/actions.md)
**Get an organization variable**
**Operation ID:** `actions/get-org-variable`

Gets a specific variable in an organization.

The authenticated user must have collaborator access to a repository to create, update, or read variables.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[organization-actions-variable](../schemas/organization-actions-variable/organization-actions-variable.md)

