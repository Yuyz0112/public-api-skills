# GET /user/starred/{owner}/{repo}

**Resource:** [activity](../resources/activity.md)
**Check if a repository is starred by the authenticated user**
**Operation ID:** `activity/check-repo-is-starred-by-authenticated-user`

Whether the authenticated user has starred the repository.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response if this repository is starred by you |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | Not Found if this repository is not starred by you |

