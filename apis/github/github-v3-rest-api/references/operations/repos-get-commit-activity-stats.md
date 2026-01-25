# GET /repos/{owner}/{repo}/stats/commit_activity

**Resource:** [repos](../resources/repos.md)
**Get the last year of commit activity**
**Operation ID:** `repos/get-commit-activity-stats`

Returns the last year of commit activity grouped by week. The `days` array is a group of commits per day, starting on `Sunday`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 202 | (reference) |
| 204 | (reference) |

**Success Response Schema:**

Array of [commit-activity](../schemas/commit-activity/commit-activity.md)

