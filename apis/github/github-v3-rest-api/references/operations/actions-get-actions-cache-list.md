# GET /repos/{owner}/{repo}/actions/caches

**Resource:** [actions](../resources/actions.md)
**List GitHub Actions caches for a repository**
**Operation ID:** `actions/get-actions-cache-list`

Lists the GitHub Actions caches for a repository.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-cache-list](../schemas/actions-cache-list/actions-cache-list.md)

