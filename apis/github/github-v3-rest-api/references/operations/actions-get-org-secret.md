# GET /orgs/{org}/actions/secrets/{secret_name}

**Resource:** [actions](../resources/actions.md)
**Get an organization secret**
**Operation ID:** `actions/get-org-secret`

Gets a single organization secret without revealing its encrypted value.

The authenticated user must have collaborator access to a repository to create, update, or read secrets

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[organization-actions-secret](../schemas/organization-actions-secret/organization-actions-secret.md)

