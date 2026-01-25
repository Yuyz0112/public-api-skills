# POST /v1/shipping_rates/{shipping_rate_token}

**Resource:** [shipping_rates](../resources/shipping-rates.md)
**Update a shipping rate**
**Operation ID:** `PostShippingRatesShippingRateToken`

<p>Updates an existing shipping rate object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

