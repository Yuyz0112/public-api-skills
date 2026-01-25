# GET /orgs/{org}/actions/cache/usage

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions cache usage for an organization**
**Operation ID:** `actions/get-actions-cache-usage-for-org`

Gets the total GitHub Actions cache usage for an organization.
The data fetched using this API is refreshed approximately every 5 minutes, so values returned from this endpoint may take at least 5 minutes to get updated.

OAuth tokens and personal access tokens (classic) need the `read:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-cache-usage-org-enterprise](../schemas/actions-cache-usage-org-enterprise/actions-cache-usage-org-enterprise.md)

