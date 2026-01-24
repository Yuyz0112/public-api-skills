# DELETE /v1/subscription_items/{item}

**Resource:** [subscription_items](../resources/subscription-items.md)
**Delete a subscription item**
**Operation ID:** `DeleteSubscriptionItemsItem`

<p>Deletes an item from the subscription. Removing a subscription item from a subscription will not cancel the subscription.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `item` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_subscription_item](../schemas/deleted/deleted-subscription-item.md)

