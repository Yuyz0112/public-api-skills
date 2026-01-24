# DELETE /v1/products/{product}/features/{id}

**Resource:** [products](../resources/products.md)
**Remove a feature from a product**
**Operation ID:** `DeleteProductsProductFeaturesId`

<p>Deletes the feature attachment to a product</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `product` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_product_feature](../schemas/deleted/deleted-product-feature.md)

