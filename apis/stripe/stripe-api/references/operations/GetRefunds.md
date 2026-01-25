# GET /v1/refunds

**Resource:** [refunds](../resources/refunds.md)
**List all refunds**
**Operation ID:** `GetRefunds`

<p>Returns a list of all refunds you created. We return the refunds in sorted order, with the most recent refunds appearing first. The 10 most recent refunds are always available by default on the Charge object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `charge` | query | string | No | Only return refunds for the charge specified by this charge ID. |
| `created` | query | any | No | Only return refunds that were created during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `payment_intent` | query | string | No | Only return refunds for the PaymentIntent specified by this ID. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

