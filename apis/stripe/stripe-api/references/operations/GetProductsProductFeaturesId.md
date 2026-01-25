# GET /v1/products/{product}/features/{id}

**Resource:** [products](../resources/products.md)
**Retrieve a product_feature**
**Operation ID:** `GetProductsProductFeaturesId`

<p>Retrieves a product_feature, which represents a feature attachment to a product</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | The ID of the product_feature. |
| `product` | path | string | Yes | The ID of the product. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[product_feature](../schemas/product/product-feature.md)

