# POST /v1/shipping_rates

**Resource:** [shipping_rates](../resources/shipping-rates.md)
**Create a shipping rate**
**Operation ID:** `PostShippingRates`

<p>Creates a new shipping rate object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[shipping_rate](../schemas/shipping/shipping-rate.md)

