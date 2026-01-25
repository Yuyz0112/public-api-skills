# PUT /2/activity/subscriptions/{subscription_id}

**Resource:** [Activity](../resources/Activity.md)
**Update X activity subscription**
**Operation ID:** `updateActivitySubscription`

Updates a subscription for an X activity event

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription_id` | path | ActivitySubscriptionId | Yes | The ID of the subscription to update. |

## Request Body

**Content Types:** `application/json`

**Schema:** [ActivitySubscriptionUpdateRequest](../schemas/Activity/ActivitySubscriptionUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ActivitySubscriptionUpdateResponse](../schemas/Activity/ActivitySubscriptionUpdateResponse.md)

## Security

- **BearerToken**
