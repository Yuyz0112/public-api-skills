# POST /v1/climate/orders/{order}

**Resource:** [climate](../resources/climate.md)
**Update an order**
**Operation ID:** `PostClimateOrdersOrder`

<p>Updates the specified order by setting the values of the parameters passed.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order` | path | string | Yes | Unique identifier of the order. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[climate.order](../schemas/climate-order/climate-order.md)

