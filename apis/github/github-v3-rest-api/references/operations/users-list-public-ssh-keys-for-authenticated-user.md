# GET /user/keys

**Resource:** [users](../resources/users.md)
**List public SSH keys for the authenticated user**
**Operation ID:** `users/list-public-ssh-keys-for-authenticated-user`

Lists the public SSH keys for the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `read:public_key` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [key](../schemas/key/key.md)

