# GET /user/subscriptions

**Resource:** [User Subscription](../resources/User-Subscription.md)
**Get User Subscriptions**
**Operation ID:** `user-subscription-get-user-subscriptions`

Lists all of a user's subscriptions.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get User Subscriptions response |
| 4XX | Get User Subscriptions response failure |

**Success Response Schema:**

[bill-subs-api_user_subscription_response_collection](../schemas/bill-subs-api/bill-subs-api-user-subscription-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
