# POST /user/gpg_keys

**Resource:** [users](../resources/users.md)
**Create a GPG key for the authenticated user**
**Operation ID:** `users/create-gpg-key-for-authenticated-user`

Adds a GPG key to the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `write:gpg_key` scope to use this endpoint.

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

[gpg-key](../schemas/gpg-key/gpg-key.md)

