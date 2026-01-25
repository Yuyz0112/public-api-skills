# DELETE /users/{id}/sessions/{type}/{session_id}

**Resource:** [Users](../resources/Users.md)
**Delete a user's session**
**Operation ID:** `deleteUserSession`
⚠️ **Deprecated**

<!-- theme: warning -->
> ### Deprecated
> This endpoint is deprecated as OAuth token revocation is now synchronous. Please use the [DELETE /oauth_delegations endpoint](https://developer.pagerduty.com/api-reference/ad1161db75db1-delete-all-o-auth-delegations) instead.

Delete a user's session.

Beginning November 2021, user sessions no longer includes newly issued OAuth tokens.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:sessions.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The user session was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

