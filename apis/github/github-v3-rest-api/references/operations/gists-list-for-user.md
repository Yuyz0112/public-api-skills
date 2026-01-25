# GET /users/{username}/gists

**Resource:** [gists](../resources/gists.md)
**List gists for a user**
**Operation ID:** `gists/list-for-user`

Lists public gists for the specified user:

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

Array of [base-gist](../schemas/base-gist/base-gist.md)

