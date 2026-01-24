# GET /v1/customers/{customer}/cards/{id}

**Resource:** [customers](../resources/customers.md)
**Retrieve a card**
**Operation ID:** `GetCustomersCustomerCardsId`
⚠️ **Deprecated**

<p>You can always see the 10 most recent cards directly on a customer; this method lets you retrieve details about a specific card stored on the customer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[card](../schemas/card/card.md)

