# GET /user/ssh_signing_keys/{ssh_signing_key_id}

**Resource:** [users](../resources/users.md)
**Get an SSH signing key for the authenticated user**
**Operation ID:** `users/get-ssh-signing-key-for-authenticated-user`

Gets extended details for an SSH signing key.

OAuth app tokens and personal access tokens (classic) need the `read:ssh_signing_key` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ssh-signing-key](../schemas/ssh-signing-key/ssh-signing-key.md)

