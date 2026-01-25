# POST /repos/{owner}/{repo}/merges

**Resource:** [repos](../resources/repos.md)
**Merge a branch**
**Operation ID:** `repos/merge`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful Response (The resulting merge commit) |
| 204 | Response when already merged |
| 403 | (reference) |
| 404 | Not Found when the base or head does not exist |
| 409 | Conflict when there is a merge conflict |
| 422 | (reference) |

**Success Response Schema:**

[commit](../schemas/commit/commit.md)

