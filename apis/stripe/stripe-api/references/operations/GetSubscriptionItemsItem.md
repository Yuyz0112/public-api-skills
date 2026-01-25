# GET /v1/subscription_items/{item}

**Resource:** [subscription_items](../resources/subscription-items.md)
**Retrieve a subscription item**
**Operation ID:** `GetSubscriptionItemsItem`

<p>Retrieves the subscription item with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

