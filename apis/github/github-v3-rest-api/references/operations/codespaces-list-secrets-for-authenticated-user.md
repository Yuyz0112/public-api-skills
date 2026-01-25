# GET /user/codespaces/secrets

**Resource:** [codespaces](../resources/codespaces.md)
**List secrets for the authenticated user**
**Operation ID:** `codespaces/list-secrets-for-authenticated-user`

Lists all development environment secrets available for a user's codespaces without revealing their
encrypted values.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

