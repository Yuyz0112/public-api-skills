# DELETE /2/activity/subscriptions/{subscription_id}

**Resource:** [Activity](../resources/Activity.md)
**Deletes X activity subscription**
**Operation ID:** `deleteActivitySubscription`

Deletes a subscription for an X activity event

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription_id` | path | ActivitySubscriptionId | Yes | The ID of the subscription to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ActivitySubscriptionDeleteResponse](../schemas/Activity/ActivitySubscriptionDeleteResponse.md)

## Security

- **BearerToken**
