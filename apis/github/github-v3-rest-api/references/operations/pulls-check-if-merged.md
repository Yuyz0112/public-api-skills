# GET /repos/{owner}/{repo}/pulls/{pull_number}/merge

**Resource:** [pulls](../resources/pulls.md)
**Check if a pull request has been merged**
**Operation ID:** `pulls/check-if-merged`

Checks if a pull request has been merged into the base branch. The HTTP status of the response indicates whether or not the pull request has been merged; the response body is empty.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response if pull request has been merged |
| 404 | Not Found if pull request has not been merged |

