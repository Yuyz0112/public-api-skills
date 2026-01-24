# POST /v1/products/{id}

**Resource:** [products](../resources/products.md)
**Update a product**
**Operation ID:** `PostProductsId`

<p>Updates the specific product by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[product](../schemas/product/product.md)

