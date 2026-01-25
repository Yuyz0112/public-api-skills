# GET /orgs/{org}/actions/cache/usage-by-repository

**Resource:** [actions](../resources/actions.md)
**List repositories with GitHub Actions cache usage for an organization**
**Operation ID:** `actions/get-actions-cache-usage-by-repo-for-org`

Lists repositories and their GitHub Actions cache usage for an organization.
The data fetched using this API is refreshed approximately every 5 minutes, so values returned from this endpoint may take at least 5 minutes to get updated.

OAuth tokens and personal access tokens (classic) need the `read:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

