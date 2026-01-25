# DELETE /user/keys/{key_id}

**Resource:** [users](../resources/users.md)
**Delete a public SSH key for the authenticated user**
**Operation ID:** `users/delete-public-ssh-key-for-authenticated-user`

Removes a public SSH key from the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `admin:public_key` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

