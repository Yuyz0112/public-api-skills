# POST /user/keys

**Resource:** [users](../resources/users.md)
**Create a public SSH key for the authenticated user**
**Operation ID:** `users/create-public-ssh-key-for-authenticated-user`

Adds a public SSH key to the authenticated user's GitHub account.

OAuth app tokens and personal access tokens (classic) need the `write:public_key` scope to use this endpoint.

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

[key](../schemas/key/key.md)

