# POST /v1/subscription_items/{item}

**Resource:** [subscription_items](../resources/subscription-items.md)
**Update a subscription item**
**Operation ID:** `PostSubscriptionItemsItem`

<p>Updates the plan or quantity of an item on a current subscription.</p>

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

[subscription_item](../schemas/subscription/subscription-item.md)

