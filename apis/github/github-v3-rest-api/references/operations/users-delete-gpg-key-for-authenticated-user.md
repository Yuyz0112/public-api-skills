# DELETE /user/gpg_keys/{gpg_key_id}

**Resource:** [users](../resources/users.md)
**Delete a GPG key for the authenticated user**
**Operation ID:** `users/delete-gpg-key-for-authenticated-user`

Removes a GPG key from the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `admin:gpg_key` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

