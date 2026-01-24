# GET /v1/prices

**Resource:** [prices](../resources/prices.md)
**List all prices**
**Operation ID:** `GetPrices`

<p>Returns a list of your active prices, excluding <a href="/docs/products-prices/pricing-models#inline-pricing">inline prices</a>. For the list of inactive prices, set <code>active</code> to false.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `active` | query | boolean | No | Only return prices that are active or inactive (e.g., pass `false` to list all inactive prices). |
| `created` | query | any | No | A filter on the list, based on the object `created` field. The value can be a string with an integer Unix timestamp, or it can be a dictionary with a number of different query options. |
| `currency` | query | string (currency) | No | Only return prices for the given currency. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `lookup_keys` | query | string[] | No | Only return the price with these lookup_keys, if any exist. You can specify up to 10 lookup_keys. |
| `product` | query | string | No | Only return prices for the given product. |
| `recurring` | query | object | No | Only return prices with these recurring fields. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `type` | query | enum: one_time, recurring | No | Only return prices of type `recurring` or `one_time`. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

