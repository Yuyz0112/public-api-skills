# DELETE /oauth_delegations

**Resource:** [OAuth Delegations](../resources/OAuth-Delegations.md)
**Delete all OAuth delegations**
**Operation ID:** `deleteOauthDelegations`

Delete all OAuth delegations as per provided query parameters.

An OAuth delegation represents an instance of a user or account's authorization to an app (via OAuth) to access their PagerDuty account.
Common apps include the PagerDuty mobile app, Slack, Microsoft Teams, and third-party apps. It also represents a user session in the PagerDuty web app.

Deleting an OAuth delegation will revoke that instance of an app's access to that user or account.
To grant access again, reauthorization/reauthentication will be required.

This endpoint supports deleting mobile app OAuth delegations for a given user, which is equivalent to signing users out of the mobile app. It also supports deleting delegations of type web, which is equivalent to signing users out of the web app.

This is a synchronous API.

Scoped OAuth requires: `oauth_delegations.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The request to delete delegations has been processed. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

