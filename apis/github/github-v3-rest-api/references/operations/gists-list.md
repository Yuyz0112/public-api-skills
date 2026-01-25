# GET /gists

**Resource:** [gists](../resources/gists.md)
**List gists for the authenticated user**
**Operation ID:** `gists/list`

Lists the authenticated user's gists or if called anonymously, this endpoint returns all public gists:

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [base-gist](../schemas/base-gist/base-gist.md)

