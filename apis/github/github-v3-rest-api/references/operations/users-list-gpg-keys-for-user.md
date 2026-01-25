# GET /users/{username}/gpg_keys

**Resource:** [users](../resources/users.md)
**List GPG keys for a user**
**Operation ID:** `users/list-gpg-keys-for-user`

Lists the GPG keys for a user. This information is accessible by anyone.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [gpg-key](../schemas/gpg-key/gpg-key.md)

