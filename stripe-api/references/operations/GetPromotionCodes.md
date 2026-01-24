# GET /v1/promotion_codes

**Resource:** [promotion_codes](../resources/promotion-codes.md)
**List all promotion codes**
**Operation ID:** `GetPromotionCodes`

<p>Returns a list of your promotion codes.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `active` | query | boolean | No | Filter promotion codes by whether they are active. |
| `code` | query | string | No | Only return promotion codes that have this case-insensitive code. |
| `coupon` | query | string | No | Only return promotion codes for this coupon. |
| `created` | query | any | No | A filter on the list, based on the object `created` field. The value can be a string with an integer Unix timestamp, or it can be a dictionary with a number of different query options. |
| `customer` | query | string | No | Only return promotion codes that are restricted to this customer. |
| `customer_account` | query | string | No | Only return promotion codes that are restricted to this account representing the customer. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

