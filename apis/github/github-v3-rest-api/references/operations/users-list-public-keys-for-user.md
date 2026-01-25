# GET /users/{username}/keys

**Resource:** [users](../resources/users.md)
**List public keys for a user**
**Operation ID:** `users/list-public-keys-for-user`

Lists the _verified_ public SSH keys for a user. This is accessible by anyone.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [key-simple](../schemas/key-simple/key-simple.md)

