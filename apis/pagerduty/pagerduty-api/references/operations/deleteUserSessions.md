# DELETE /users/{id}/sessions

**Resource:** [Users](../resources/Users.md)
**Delete all user sessions**
**Operation ID:** `deleteUserSessions`
⚠️ **Deprecated**

<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated as OAuth token revocation is now synchronous. Please use the [DELETE /oauth_delegations endpoint](https://developer.pagerduty.com/api-reference/ad1161db75db1-delete-all-o-auth-delegations) instead.

Delete all user sessions.

Beginning November 2021, user sessions no longer includes newly issued OAuth tokens.

If you are interested in deleting mobile app sessions, refer to the Delete OAuth Delegations endpoint.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:sessions.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The user sessions were all deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

