# GET /user/gpg_keys

**Resource:** [users](../resources/users.md)
**List GPG keys for the authenticated user**
**Operation ID:** `users/list-gpg-keys-for-authenticated-user`

Lists the current user's GPG keys.

OAuth app tokens and personal access tokens (classic) need the `read:gpg_key` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [gpg-key](../schemas/gpg-key/gpg-key.md)

