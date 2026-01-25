# POST /repos/{owner}/{repo}/git/blobs

**Resource:** [git](../resources/git.md)
**Create a blob**
**Operation ID:** `git/create-blob`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | Validation failed |

**Success Response Schema:**

[short-blob](../schemas/short-blob/short-blob.md)

