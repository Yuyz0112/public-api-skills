# GET /users/me

**Resource:** [Users](../resources/Users.md)
**Get the current user**
**Operation ID:** `getCurrentUser`

Get details about the current user.

This endpoint can only be used with a [user-level API key](https://support.pagerduty.com/docs/using-the-api#section-generating-a-personal-rest-api-key) or a key generated through an OAuth flow. This will not work if the request is made with an account-level access token.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)


## Responses

| Status | Description |
|--------|-------------|
| 200 | The requesting user. |
| 400 | (reference) |
| 429 | (reference) |

