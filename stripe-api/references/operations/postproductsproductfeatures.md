# POST /v1/products/{product}/features

**Resource:** [products](../resources/products.md)
**Attach a feature to a product**
**Operation ID:** `PostProductsProductFeatures`

<p>Creates a product_feature, which represents a feature attachment to a product</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `product` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[product_feature](../schemas/product/product-feature.md)

