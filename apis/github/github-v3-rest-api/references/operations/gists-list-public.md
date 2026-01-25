# GET /gists/public

**Resource:** [gists](../resources/gists.md)
**List public gists**
**Operation ID:** `gists/list-public`

List public gists sorted by most recently updated to least recently updated.

Note: With [pagination](https://docs.github.com/rest/guides/using-pagination-in-the-rest-api), you can fetch up to 3000 gists. For example, you can fetch 100 pages with 30 gists per page or 30 pages with 100 gists per page.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [base-gist](../schemas/base-gist/base-gist.md)

