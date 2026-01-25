# POST /v1/climate/orders

**Resource:** [climate](../resources/climate.md)
**Create an order**
**Operation ID:** `PostClimateOrders`

<p>Creates a Climate order object for a given Climate product. The order will be processed immediately
after creation and payment will be deducted your Stripe balance.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[climate.order](../schemas/climate-order/climate-order.md)

