# GET /v1/climate/products/{product}

**Resource:** [climate](../resources/climate.md)
**Retrieve a product**
**Operation ID:** `GetClimateProductsProduct`

<p>Retrieves the details of a Climate product with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `product` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[climate.product](../schemas/climate-product/climate-product.md)

