# DELETE /user/ssh_signing_keys/{ssh_signing_key_id}

**Resource:** [users](../resources/users.md)
**Delete an SSH signing key for the authenticated user**
**Operation ID:** `users/delete-ssh-signing-key-for-authenticated-user`

Deletes an SSH signing key from the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `admin:ssh_signing_key` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

