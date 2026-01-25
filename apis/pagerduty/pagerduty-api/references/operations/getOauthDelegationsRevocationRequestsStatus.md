# GET /oauth_delegations/revocation_requests/status

**Resource:** [OAuth Delegations](../resources/OAuth-Delegations.md)
**Get OAuth delegations revocation requests status**
**Operation ID:** `getOauthDelegationsRevocationRequestsStatus`
⚠️ **Deprecated**

<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated as OAuth token revocation is now synchronous. Please use the [DELETE /oauth_delegations endpoint](https://developer.pagerduty.com/api-reference/ad1161db75db1-delete-all-o-auth-delegations) instead.

Get the status of all OAuth delegations revocation requests for this account, specifically how many requests are still pending. As all requests are now synchronous, no pending requests will be found.

This endpoint is limited to account owners and admins.

Scoped OAuth requires: `oauth_delegations.read`


## Responses

| Status | Description |
|--------|-------------|
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

