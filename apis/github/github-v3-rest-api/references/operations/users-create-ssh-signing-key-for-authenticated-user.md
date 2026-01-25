# POST /user/ssh_signing_keys

**Resource:** [users](../resources/users.md)
**Create a SSH signing key for the authenticated user**
**Operation ID:** `users/create-ssh-signing-key-for-authenticated-user`

Creates an SSH signing key for the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `write:ssh_signing_key` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[ssh-signing-key](../schemas/ssh-signing-key/ssh-signing-key.md)

