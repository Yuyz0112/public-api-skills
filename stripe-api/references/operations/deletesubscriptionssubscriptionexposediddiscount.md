# DELETE /v1/subscriptions/{subscription_exposed_id}/discount

**Resource:** [subscriptions](../resources/subscriptions.md)
**Delete a subscription discount**
**Operation ID:** `DeleteSubscriptionsSubscriptionExposedIdDiscount`

<p>Removes the currently applied discount on a subscription.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription_exposed_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_discount](../schemas/deleted/deleted-discount.md)

