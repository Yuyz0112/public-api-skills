# POST /v1/prices/{price}

**Resource:** [prices](../resources/prices.md)
**Update a price**
**Operation ID:** `PostPricesPrice`

<p>Updates the specified price by setting the values of the parameters passed. Any parameters not provided are left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

