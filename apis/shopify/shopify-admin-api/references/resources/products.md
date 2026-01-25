# products

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-collects.md) |
| POST | `/admin/api/2020-01/collects.json` | Adds a product to a custom collection. | [View](../operations/deprecated-202001-create-collects.md) |
| GET | `/admin/api/2020-01/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/deprecated-202001-get-collects-param-collect-id.md) |
| DELETE | `/admin/api/2020-01/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/deprecated-202001-delete-collects-param-collect-id.md) |
| GET | `/admin/api/2020-01/collects/count.json` | Retrieves a count of collects. | [View](../operations/deprecated-202001-get-collects-count.md) |
| GET | `/admin/api/2020-04/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-collects.md) |
| POST | `/admin/api/2020-04/collects.json` | Adds a product to a custom collection. | [View](../operations/deprecated-202004-create-collects.md) |
| GET | `/admin/api/2020-04/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/deprecated-202004-get-collects-param-collect-id.md) |
| DELETE | `/admin/api/2020-04/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/deprecated-202004-delete-collects-param-collect-id.md) |
| GET | `/admin/api/2020-04/collects/count.json` | Retrieves a count of collects. | [View](../operations/deprecated-202004-get-collects-count.md) |
| GET | `/admin/api/2020-07/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-collects.md) |
| POST | `/admin/api/2020-07/collects.json` | Adds a product to a custom collection. | [View](../operations/deprecated-202007-create-collects.md) |
| GET | `/admin/api/2020-07/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/deprecated-202007-get-collects-param-collect-id.md) |
| DELETE | `/admin/api/2020-07/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/deprecated-202007-delete-collects-param-collect-id.md) |
| GET | `/admin/api/2020-07/collects/count.json` | Retrieves a count of collects. | [View](../operations/deprecated-202007-get-collects-count.md) |
| GET | `/admin/api/2020-10/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-collects.md) |
| POST | `/admin/api/2020-10/collects.json` | Adds a product to a custom collection. | [View](../operations/create-collects.md) |
| GET | `/admin/api/2020-10/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/get-collects-param-collect-id.md) |
| DELETE | `/admin/api/2020-10/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/delete-collects-param-collect-id.md) |
| GET | `/admin/api/2020-10/collects/count.json` | Retrieves a count of collects. | [View](../operations/get-collects-count.md) |
| GET | `/admin/api/2021-01/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-collects.md) |
| POST | `/admin/api/2021-01/collects.json` | Adds a product to a custom collection. | [View](../operations/deprecated-202101-create-collects.md) |
| GET | `/admin/api/2021-01/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/deprecated-202101-get-collects-param-collect-id.md) |
| DELETE | `/admin/api/2021-01/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/deprecated-202101-delete-collects-param-collect-id.md) |
| GET | `/admin/api/2021-01/collects/count.json` | Retrieves a count of collects. | [View](../operations/deprecated-202101-get-collects-count.md) |
| GET | `/admin/api/unstable/collects.json` | Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-collects.md) |
| POST | `/admin/api/unstable/collects.json` | Adds a product to a custom collection. | [View](../operations/deprecated-unstable-create-collects.md) |
| GET | `/admin/api/unstable/collects/{collect_id}.json` | Retrieves a specific collect by its ID. | [View](../operations/deprecated-unstable-get-collects-param-collect-id.md) |
| DELETE | `/admin/api/unstable/collects/{collect_id}.json` | Removes a product from a collection. | [View](../operations/deprecated-unstable-delete-collects-param-collect-id.md) |
| GET | `/admin/api/unstable/collects/count.json` | Retrieves a count of collects. | [View](../operations/deprecated-unstable-get-collects-count.md) |
| GET | `/admin/api/2020-01/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/deprecated-202001-get-collections-param-collection-id.md) |
| GET | `/admin/api/2020-01/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/deprecated-202001-get-collections-param-collection-id-products.md) |
| GET | `/admin/api/2020-04/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/deprecated-202004-get-collections-param-collection-id.md) |
| GET | `/admin/api/2020-04/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/deprecated-202004-get-collections-param-collection-id-products.md) |
| GET | `/admin/api/2020-07/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/deprecated-202007-get-collections-param-collection-id.md) |
| GET | `/admin/api/2020-07/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/deprecated-202007-get-collections-param-collection-id-products.md) |
| GET | `/admin/api/2020-10/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/get-collections-param-collection-id.md) |
| GET | `/admin/api/2020-10/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/get-collections-param-collection-id-products.md) |
| GET | `/admin/api/2021-01/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/deprecated-202101-get-collections-param-collection-id.md) |
| GET | `/admin/api/2021-01/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/deprecated-202101-get-collections-param-collection-id-products.md) |
| GET | `/admin/api/unstable/collections/{collection_id}.json` | Retrieves a single collection | [View](../operations/deprecated-unstable-get-collections-param-collection-id.md) |
| GET | `/admin/api/unstable/collections/{collection_id}/products.json` | Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order. | [View](../operations/deprecated-unstable-get-collections-param-collection-id-products.md) |
| GET | `/admin/api/2020-01/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-custom-collections.md) |
| POST | `/admin/api/2020-01/custom_collections.json` | Creates a custom collection | [View](../operations/deprecated-202001-create-custom-collections.md) |
| GET | `/admin/api/2020-01/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/deprecated-202001-get-custom-collections-count.md) |
| GET | `/admin/api/2020-01/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/deprecated-202001-get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/2020-01/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/deprecated-202001-update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/2020-01/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/deprecated-202001-delete-custom-collections-param-custom-collection-id.md) |
| GET | `/admin/api/2020-04/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-custom-collections.md) |
| POST | `/admin/api/2020-04/custom_collections.json` | Creates a custom collection | [View](../operations/deprecated-202004-create-custom-collections.md) |
| GET | `/admin/api/2020-04/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/deprecated-202004-get-custom-collections-count.md) |
| GET | `/admin/api/2020-04/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/deprecated-202004-get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/2020-04/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/deprecated-202004-update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/2020-04/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/deprecated-202004-delete-custom-collections-param-custom-collection-id.md) |
| GET | `/admin/api/2020-07/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-custom-collections.md) |
| POST | `/admin/api/2020-07/custom_collections.json` | Creates a custom collection | [View](../operations/deprecated-202007-create-custom-collections.md) |
| GET | `/admin/api/2020-07/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/deprecated-202007-get-custom-collections-count.md) |
| GET | `/admin/api/2020-07/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/deprecated-202007-get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/2020-07/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/deprecated-202007-update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/2020-07/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/deprecated-202007-delete-custom-collections-param-custom-collection-id.md) |
| GET | `/admin/api/2020-10/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-custom-collections.md) |
| POST | `/admin/api/2020-10/custom_collections.json` | Creates a custom collection | [View](../operations/create-custom-collections.md) |
| GET | `/admin/api/2020-10/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/get-custom-collections-count.md) |
| GET | `/admin/api/2020-10/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/2020-10/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/2020-10/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/delete-custom-collections-param-custom-collection-id.md) |
| GET | `/admin/api/2021-01/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-custom-collections.md) |
| POST | `/admin/api/2021-01/custom_collections.json` | Creates a custom collection | [View](../operations/deprecated-202101-create-custom-collections.md) |
| GET | `/admin/api/2021-01/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/deprecated-202101-get-custom-collections-count.md) |
| GET | `/admin/api/2021-01/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/deprecated-202101-get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/2021-01/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/deprecated-202101-update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/2021-01/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/deprecated-202101-delete-custom-collections-param-custom-collection-id.md) |
| GET | `/admin/api/unstable/custom_collections.json` | Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-custom-collections.md) |
| POST | `/admin/api/unstable/custom_collections.json` | Creates a custom collection | [View](../operations/deprecated-unstable-create-custom-collections.md) |
| GET | `/admin/api/unstable/custom_collections/count.json` | Retrieves a count of custom collections | [View](../operations/deprecated-unstable-get-custom-collections-count.md) |
| GET | `/admin/api/unstable/custom_collections/{custom_collection_id}.json` | Retrieves a single custom collection | [View](../operations/deprecated-unstable-get-custom-collections-param-custom-collection-id.md) |
| PUT | `/admin/api/unstable/custom_collections/{custom_collection_id}.json` | Updates an existing custom collection | [View](../operations/deprecated-unstable-update-custom-collections-param-custom-collection-id.md) |
| DELETE | `/admin/api/unstable/custom_collections/{custom_collection_id}.json` | Deletes a custom collection | [View](../operations/deprecated-unstable-delete-custom-collections-param-custom-collection-id.md) |
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
| GET | `/admin/api/2020-01/products/{product_id}/images.json` | Get all product images | [View](../operations/deprecated-202001-get-products-param-product-id-images.md) |
| POST | `/admin/api/2020-01/products/{product_id}/images.json` | Create a new product image | [View](../operations/deprecated-202001-create-products-param-product-id-images.md) |
| GET | `/admin/api/2020-01/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/deprecated-202001-get-products-param-product-id-images-count.md) |
| GET | `/admin/api/2020-01/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/deprecated-202001-get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/2020-01/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/deprecated-202001-update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/2020-01/products/{product_id}/images/{image_id}.json` |  | [View](../operations/deprecated-202001-delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/2020-04/products/{product_id}/images.json` | Get all product images | [View](../operations/deprecated-202004-get-products-param-product-id-images.md) |
| POST | `/admin/api/2020-04/products/{product_id}/images.json` | Create a new product image | [View](../operations/deprecated-202004-create-products-param-product-id-images.md) |
| GET | `/admin/api/2020-04/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/deprecated-202004-get-products-param-product-id-images-count.md) |
| GET | `/admin/api/2020-04/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/deprecated-202004-get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/2020-04/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/deprecated-202004-update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/2020-04/products/{product_id}/images/{image_id}.json` |  | [View](../operations/deprecated-202004-delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/2020-07/products/{product_id}/images.json` | Get all product images | [View](../operations/deprecated-202007-get-products-param-product-id-images.md) |
| POST | `/admin/api/2020-07/products/{product_id}/images.json` | Create a new product image | [View](../operations/deprecated-202007-create-products-param-product-id-images.md) |
| GET | `/admin/api/2020-07/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/deprecated-202007-get-products-param-product-id-images-count.md) |
| GET | `/admin/api/2020-07/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/deprecated-202007-get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/2020-07/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/deprecated-202007-update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/2020-07/products/{product_id}/images/{image_id}.json` |  | [View](../operations/deprecated-202007-delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/2020-10/products/{product_id}/images.json` | Get all product images | [View](../operations/get-products-param-product-id-images.md) |
| POST | `/admin/api/2020-10/products/{product_id}/images.json` | Create a new product image | [View](../operations/create-products-param-product-id-images.md) |
| GET | `/admin/api/2020-10/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/get-products-param-product-id-images-count.md) |
| GET | `/admin/api/2020-10/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/2020-10/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/2020-10/products/{product_id}/images/{image_id}.json` |  | [View](../operations/delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/2021-01/products/{product_id}/images.json` | Get all product images | [View](../operations/deprecated-202101-get-products-param-product-id-images.md) |
| POST | `/admin/api/2021-01/products/{product_id}/images.json` | Create a new product image | [View](../operations/deprecated-202101-create-products-param-product-id-images.md) |
| GET | `/admin/api/2021-01/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/deprecated-202101-get-products-param-product-id-images-count.md) |
| GET | `/admin/api/2021-01/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/deprecated-202101-get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/2021-01/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/deprecated-202101-update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/2021-01/products/{product_id}/images/{image_id}.json` |  | [View](../operations/deprecated-202101-delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/unstable/products/{product_id}/images.json` | Get all product images | [View](../operations/deprecated-unstable-get-products-param-product-id-images.md) |
| POST | `/admin/api/unstable/products/{product_id}/images.json` | Create a new product image | [View](../operations/deprecated-unstable-create-products-param-product-id-images.md) |
| GET | `/admin/api/unstable/products/{product_id}/images/count.json` | Get a count of all product images | [View](../operations/deprecated-unstable-get-products-param-product-id-images-count.md) |
| GET | `/admin/api/unstable/products/{product_id}/images/{image_id}.json` | Get a single product image by id | [View](../operations/deprecated-unstable-get-products-param-product-id-images-param-image-id.md) |
| PUT | `/admin/api/unstable/products/{product_id}/images/{image_id}.json` | Modify an existing product image | [View](../operations/deprecated-unstable-update-products-param-product-id-images-param-image-id.md) |
| DELETE | `/admin/api/unstable/products/{product_id}/images/{image_id}.json` |  | [View](../operations/deprecated-unstable-delete-products-param-product-id-images-param-image-id.md) |
| GET | `/admin/api/2020-01/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-smart-collections.md) |
| POST | `/admin/api/2020-01/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/deprecated-202001-create-smart-collections.md) |
| GET | `/admin/api/2020-01/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/deprecated-202001-get-smart-collections-count.md) |
| GET | `/admin/api/2020-01/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/deprecated-202001-get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-01/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/deprecated-202001-update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/2020-01/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/deprecated-202001-delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-01/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/deprecated-202001-update-smart-collections-param-smart-collection-id-order.md) |
| GET | `/admin/api/2020-04/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-smart-collections.md) |
| POST | `/admin/api/2020-04/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/deprecated-202004-create-smart-collections.md) |
| GET | `/admin/api/2020-04/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/deprecated-202004-get-smart-collections-count.md) |
| GET | `/admin/api/2020-04/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/deprecated-202004-get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-04/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/deprecated-202004-update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/2020-04/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/deprecated-202004-delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-04/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/deprecated-202004-update-smart-collections-param-smart-collection-id-order.md) |
| GET | `/admin/api/2020-07/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-smart-collections.md) |
| POST | `/admin/api/2020-07/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/deprecated-202007-create-smart-collections.md) |
| GET | `/admin/api/2020-07/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/deprecated-202007-get-smart-collections-count.md) |
| GET | `/admin/api/2020-07/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/deprecated-202007-get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-07/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/deprecated-202007-update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/2020-07/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/deprecated-202007-delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-07/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/deprecated-202007-update-smart-collections-param-smart-collection-id-order.md) |
| GET | `/admin/api/2020-10/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-smart-collections.md) |
| POST | `/admin/api/2020-10/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/create-smart-collections.md) |
| GET | `/admin/api/2020-10/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/get-smart-collections-count.md) |
| GET | `/admin/api/2020-10/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-10/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/2020-10/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2020-10/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/update-smart-collections-param-smart-collection-id-order.md) |
| GET | `/admin/api/2021-01/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-smart-collections.md) |
| POST | `/admin/api/2021-01/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/deprecated-202101-create-smart-collections.md) |
| GET | `/admin/api/2021-01/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/deprecated-202101-get-smart-collections-count.md) |
| GET | `/admin/api/2021-01/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/deprecated-202101-get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2021-01/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/deprecated-202101-update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/2021-01/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/deprecated-202101-delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/2021-01/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/deprecated-202101-update-smart-collections-param-smart-collection-id-order.md) |
| GET | `/admin/api/unstable/smart_collections.json` | Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-smart-collections.md) |
| POST | `/admin/api/unstable/smart_collections.json` | Creates a new smart collection using the specified rules. | [View](../operations/deprecated-unstable-create-smart-collections.md) |
| GET | `/admin/api/unstable/smart_collections/count.json` | Retrieves a count of smart collections | [View](../operations/deprecated-unstable-get-smart-collections-count.md) |
| GET | `/admin/api/unstable/smart_collections/{smart_collection_id}.json` | Retrieves a single smart collection | [View](../operations/deprecated-unstable-get-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/unstable/smart_collections/{smart_collection_id}.json` | Updates an existing smart collection | [View](../operations/deprecated-unstable-update-smart-collections-param-smart-collection-id.md) |
| DELETE | `/admin/api/unstable/smart_collections/{smart_collection_id}.json` | Removes a smart collection | [View](../operations/deprecated-unstable-delete-smart-collections-param-smart-collection-id.md) |
| PUT | `/admin/api/unstable/smart_collections/{smart_collection_id}/order.json` | Updates the ordering type of products in a smart collection | [View](../operations/deprecated-unstable-update-smart-collections-param-smart-collection-id-order.md) |
