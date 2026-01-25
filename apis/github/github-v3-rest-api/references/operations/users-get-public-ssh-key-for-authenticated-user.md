# GET /user/keys/{key_id}

**Resource:** [users](../resources/users.md)
**Get a public SSH key for the authenticated user**
**Operation ID:** `users/get-public-ssh-key-for-authenticated-user`

View extended details for a single public SSH key.

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

[key](../schemas/key/key.md)

