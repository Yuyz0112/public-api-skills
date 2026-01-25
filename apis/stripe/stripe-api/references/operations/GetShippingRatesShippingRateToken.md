# GET /v1/shipping_rates/{shipping_rate_token}

**Resource:** [shipping_rates](../resources/shipping-rates.md)
**Retrieve a shipping rate**
**Operation ID:** `GetShippingRatesShippingRateToken`

<p>Returns the shipping rate object with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `shipping_rate_token` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[shipping_rate](../schemas/shipping/shipping-rate.md)

