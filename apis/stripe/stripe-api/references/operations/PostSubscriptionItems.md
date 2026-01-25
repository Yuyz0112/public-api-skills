# POST /v1/subscription_items

**Resource:** [subscription_items](../resources/subscription-items.md)
**Create a subscription item**
**Operation ID:** `PostSubscriptionItems`

<p>Adds a new item to an existing subscription. No existing items will be changed or replaced.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription_item](../schemas/subscription/subscription-item.md)

