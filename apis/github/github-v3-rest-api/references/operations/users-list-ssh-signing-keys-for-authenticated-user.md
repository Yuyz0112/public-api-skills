# GET /user/ssh_signing_keys

**Resource:** [users](../resources/users.md)
**List SSH signing keys for the authenticated user**
**Operation ID:** `users/list-ssh-signing-keys-for-authenticated-user`

Lists the SSH signing keys for the authenticated user's GitHub account.

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

Array of [ssh-signing-key](../schemas/ssh-signing-key/ssh-signing-key.md)

