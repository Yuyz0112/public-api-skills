# GET /v1/checkout/sessions

**Resource:** [checkout](../resources/checkout.md)
**List all Checkout Sessions**
**Operation ID:** `GetCheckoutSessions`

<p>Returns a list of Checkout Sessions.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | any | No | Only return Checkout Sessions that were created during the given date interval. |
| `customer` | query | string | No | Only return the Checkout Sessions for the Customer specified. |
| `customer_account` | query | string | No | Only return the Checkout Sessions for the Account specified. |
| `customer_details` | query | object | No | Only return the Checkout Sessions for the Customer details specified. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `payment_intent` | query | string | No | Only return the Checkout Session for the PaymentIntent specified. |
| `payment_link` | query | string | No | Only return the Checkout Sessions for the Payment Link specified. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: complete, expired, open | No | Only return the Checkout Sessions matching the given status. |
| `subscription` | query | string | No | Only return the Checkout Session for the subscription specified. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

