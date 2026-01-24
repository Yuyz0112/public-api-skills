# GET /v1/prices/{price}

**Resource:** [prices](../resources/prices.md)
**Retrieve a price**
**Operation ID:** `GetPricesPrice`

<p>Retrieves the price with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `price` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[price](../schemas/price/price.md)

