# GET /2/account_activity/subscriptions/count

**Resource:** [Account Activity](../resources/Account-Activity.md)
**Get subscription count**
**Operation ID:** `getAccountActivitySubscriptionCount`

Retrieves a count of currently active Account Activity subscriptions.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubscriptionsCountGetResponse](../schemas/Subscriptions/SubscriptionsCountGetResponse.md)

## Security

- **BearerToken**
