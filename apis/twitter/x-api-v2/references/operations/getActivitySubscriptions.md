# GET /2/activity/subscriptions

**Resource:** [Activity](../resources/Activity.md)
**Get X activity subscriptions**
**Operation ID:** `getActivitySubscriptions`

Get a list of active subscriptions for XAA

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ActivitySubscriptionGetResponse](../schemas/Activity/ActivitySubscriptionGetResponse.md)

## Security

- **BearerToken**
