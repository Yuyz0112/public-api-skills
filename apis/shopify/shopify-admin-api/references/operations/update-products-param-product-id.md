# PUT /admin/api/2020-10/products/{product_id}.json

**Resource:** [products/product](../resources/products-product.md)
**Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag.**
**Operation ID:** `update_products_param_product_id`

https://shopify.dev/docs/admin-api/rest/reference/products/product#update-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `product_id` | path | string | Yes | product_id |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

