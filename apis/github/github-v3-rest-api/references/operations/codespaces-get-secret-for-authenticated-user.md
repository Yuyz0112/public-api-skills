# GET /user/codespaces/secrets/{secret_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Get a secret for the authenticated user**
**Operation ID:** `codespaces/get-secret-for-authenticated-user`

Gets a development environment secret available to a user's codespaces without revealing its encrypted value.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[codespaces-secret](../schemas/codespaces-secret/codespaces-secret.md)

