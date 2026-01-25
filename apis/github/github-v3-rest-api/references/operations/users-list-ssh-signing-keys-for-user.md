# GET /users/{username}/ssh_signing_keys

**Resource:** [users](../resources/users.md)
**List SSH signing keys for a user**
**Operation ID:** `users/list-ssh-signing-keys-for-user`

Lists the SSH signing keys for a user. This operation is accessible by anyone.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [ssh-signing-key](../schemas/ssh-signing-key/ssh-signing-key.md)

