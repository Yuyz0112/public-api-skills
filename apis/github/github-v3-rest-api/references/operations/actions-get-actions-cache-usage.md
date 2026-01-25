# GET /repos/{owner}/{repo}/actions/cache/usage

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions cache usage for a repository**
**Operation ID:** `actions/get-actions-cache-usage`

Gets GitHub Actions cache usage for a repository.
The data fetched using this API is refreshed approximately every 5 minutes, so values returned from this endpoint may take at least 5 minutes to get updated.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-cache-usage-by-repository](../schemas/actions-cache-usage-by-repository/actions-cache-usage-by-repository.md)

