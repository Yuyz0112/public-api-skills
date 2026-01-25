# GET /repos/{owner}/{repo}/stats/code_frequency

**Resource:** [repos](../resources/repos.md)
**Get the weekly commit activity**
**Operation ID:** `repos/get-code-frequency-stats`

Returns a weekly aggregate of the number of additions and deletions pushed to a repository.

> [!NOTE]
> This endpoint can only be used for repositories with fewer than 10,000 commits. If the repository contains 10,000 or more commits, a 422 status code will be returned.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a weekly aggregate of the number of additions and deletions pushed to a repository. |
| 202 | (reference) |
| 204 | (reference) |
| 422 | Repository contains more than 10,000 commits |

**Success Response Schema:**

Array of [code-frequency-stat](../schemas/code-frequency-stat/code-frequency-stat.md)

