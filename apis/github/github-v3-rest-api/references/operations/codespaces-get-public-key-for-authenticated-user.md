# GET /user/codespaces/secrets/public-key

**Resource:** [codespaces](../resources/codespaces.md)
**Get public key for the authenticated user**
**Operation ID:** `codespaces/get-public-key-for-authenticated-user`

Gets your public key, which you need to encrypt secrets. You need to encrypt a secret before you can create or update secrets.

The authenticated user must have Codespaces access to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `codespace` or `codespace:secrets` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[codespaces-user-public-key](../schemas/codespaces-user-public-key/codespaces-user-public-key.md)

