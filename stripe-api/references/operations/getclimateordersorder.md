# GET /v1/climate/orders/{order}

**Resource:** [climate](../resources/climate.md)
**Retrieve an order**
**Operation ID:** `GetClimateOrdersOrder`

<p>Retrieves the details of a Climate order object with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

