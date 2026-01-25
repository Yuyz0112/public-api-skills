# GET /gists/starred

**Resource:** [gists](../resources/gists.md)
**List starred gists**
**Operation ID:** `gists/list-starred`

List the authenticated user's starred gists:

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [base-gist](../schemas/base-gist/base-gist.md)

