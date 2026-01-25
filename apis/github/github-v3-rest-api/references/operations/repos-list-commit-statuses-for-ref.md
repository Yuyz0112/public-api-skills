# GET /repos/{owner}/{repo}/commits/{ref}/statuses

**Resource:** [repos](../resources/repos.md)
**List commit statuses for a reference**
**Operation ID:** `repos/list-commit-statuses-for-ref`

Users with pull access in a repository can view commit statuses for a given ref. The ref can be a SHA, a branch name, or a tag name. Statuses are returned in reverse chronological order. The first status in the list will be the latest one.

This resource is also available via a legacy route: `GET /repos/:owner/:repo/statuses/:ref`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |

**Success Response Schema:**

Array of [status](../schemas/status/status.md)

