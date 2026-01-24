# GET /v1/products

**Resource:** [products](../resources/products.md)
**List all products**
**Operation ID:** `GetProducts`

<p>Returns a list of your products. The products are returned sorted by creation date, with the most recently created products appearing first.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `active` | query | boolean | No | Only return products that are active or inactive (e.g., pass `false` to list all inactive products). |
| `created` | query | any | No | Only return products that were created during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `ids` | query | string[] | No | Only return products with the given IDs. Cannot be used with [starting_after](https://api.stripe.com#list_products-starting_after) or [ending_before](https://api.stripe.com#list_products-ending_before). |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `shippable` | query | boolean | No | Only return products that can be shipped (i.e., physical, not digital products). |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `url` | query | string | No | Only return products with the given url. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

