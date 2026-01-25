# GET /repos/{owner}/{repo}/commits/{ref}/status

**Resource:** [repos](../resources/repos.md)
**Get the combined status for a specific reference**
**Operation ID:** `repos/get-combined-status-for-ref`

Users with pull access in a repository can access a combined view of commit statuses for a given ref. The ref can be a SHA, a branch name, or a tag name.


Additionally, a combined `state` is returned. The `state` is one of:

*   **failure** if any of the contexts report as `error` or `failure`
*   **pending** if there are no statuses or a context is `pending`
*   **success** if the latest status for all contexts is `success`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[combined-commit-status](../schemas/combined-commit-status/combined-commit-status.md)

