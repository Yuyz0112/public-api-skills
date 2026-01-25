# PATCH /repos/{owner}/{repo}/releases/{release_id}

**Resource:** [repos](../resources/repos.md)
**Update a release**
**Operation ID:** `repos/update-release`

Users with push access to the repository can edit a release.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | Not Found if the discussion category name is invalid |

**Success Response Schema:**

[release](../schemas/release/release.md)

