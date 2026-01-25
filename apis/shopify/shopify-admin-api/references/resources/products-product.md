# products/product

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-products.md) |
| POST | `/admin/api/2020-01/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202001-create-products.md) |
| GET | `/admin/api/2020-01/products/count.json` | Retrieves a count of products. | [View](../operations/deprecated-202001-get-products-count.md) |
| GET | `/admin/api/2020-01/products/{product_id}.json` | Retrieves a single product. | [View](../operations/deprecated-202001-get-products-param-product-id.md) |
| PUT | `/admin/api/2020-01/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202001-update-products-param-product-id.md) |
| DELETE | `/admin/api/2020-01/products/{product_id}.json` | Deletes a product. | [View](../operations/deprecated-202001-delete-products-param-product-id.md) |
| GET | `/admin/api/2020-04/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-products.md) |
| POST | `/admin/api/2020-04/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202004-create-products.md) |
| GET | `/admin/api/2020-04/products/count.json` | Retrieves a count of products. | [View](../operations/deprecated-202004-get-products-count.md) |
| GET | `/admin/api/2020-04/products/{product_id}.json` | Retrieves a single product. | [View](../operations/deprecated-202004-get-products-param-product-id.md) |
| PUT | `/admin/api/2020-04/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202004-update-products-param-product-id.md) |
| DELETE | `/admin/api/2020-04/products/{product_id}.json` | Deletes a product. | [View](../operations/deprecated-202004-delete-products-param-product-id.md) |
| GET | `/admin/api/2020-07/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-products.md) |
| POST | `/admin/api/2020-07/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202007-create-products.md) |
| GET | `/admin/api/2020-07/products/count.json` | Retrieves a count of products. | [View](../operations/deprecated-202007-get-products-count.md) |
| GET | `/admin/api/2020-07/products/{product_id}.json` | Retrieves a single product. | [View](../operations/deprecated-202007-get-products-param-product-id.md) |
| PUT | `/admin/api/2020-07/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202007-update-products-param-product-id.md) |
| DELETE | `/admin/api/2020-07/products/{product_id}.json` | Deletes a product. | [View](../operations/deprecated-202007-delete-products-param-product-id.md) |
| GET | `/admin/api/2020-10/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-products.md) |
| POST | `/admin/api/2020-10/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/create-products.md) |
| GET | `/admin/api/2020-10/products/count.json` | Retrieves a count of products. | [View](../operations/get-products-count.md) |
| GET | `/admin/api/2020-10/products/{product_id}.json` | Retrieves a single product. | [View](../operations/get-products-param-product-id.md) |
| PUT | `/admin/api/2020-10/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/update-products-param-product-id.md) |
| DELETE | `/admin/api/2020-10/products/{product_id}.json` | Deletes a product. | [View](../operations/delete-products-param-product-id.md) |
| GET | `/admin/api/2021-01/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-products.md) |
| POST | `/admin/api/2021-01/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202101-create-products.md) |
| GET | `/admin/api/2021-01/products/count.json` | Retrieves a count of products. | [View](../operations/deprecated-202101-get-products-count.md) |
| GET | `/admin/api/2021-01/products/{product_id}.json` | Retrieves a single product. | [View](../operations/deprecated-202101-get-products-param-product-id.md) |
| PUT | `/admin/api/2021-01/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-202101-update-products-param-product-id.md) |
| DELETE | `/admin/api/2021-01/products/{product_id}.json` | Deletes a product. | [View](../operations/deprecated-202101-delete-products-param-product-id.md) |
| GET | `/admin/api/unstable/products.json` | Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-products.md) |
| POST | `/admin/api/unstable/products.json` | Creates a new product.
          If you want to set the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-unstable-create-products.md) |
| GET | `/admin/api/unstable/products/count.json` | Retrieves a count of products. | [View](../operations/deprecated-unstable-get-products-count.md) |
| GET | `/admin/api/unstable/products/{product_id}.json` | Retrieves a single product. | [View](../operations/deprecated-unstable-get-products-param-product-id.md) |
| PUT | `/admin/api/unstable/products/{product_id}.json` | Updates a product and its variants and images.
          If you want to update the product's SEO information, then you can use the following properties:
          
            metafields_global_title_tag: The name of the product used for SEO purposes. Generally added to the <meta name='title'> tag.
            metafields_global_description_tag: A description of the product used for SEO purposes. Generally added to the <meta name='description'> tag. | [View](../operations/deprecated-unstable-update-products-param-product-id.md) |
| DELETE | `/admin/api/unstable/products/{product_id}.json` | Deletes a product. | [View](../operations/deprecated-unstable-delete-products-param-product-id.md) |
