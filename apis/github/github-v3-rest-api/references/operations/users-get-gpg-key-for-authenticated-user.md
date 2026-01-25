# GET /user/gpg_keys/{gpg_key_id}

**Resource:** [users](../resources/users.md)
**Get a GPG key for the authenticated user**
**Operation ID:** `users/get-gpg-key-for-authenticated-user`

View extended details for a single GPG key.

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

[gpg-key](../schemas/gpg-key/gpg-key.md)

