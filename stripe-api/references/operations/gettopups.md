# GET /v1/topups

**Resource:** [topups](../resources/topups.md)
**List all top-ups**
**Operation ID:** `GetTopups`

<p>Returns a list of top-ups.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `amount` | query | any | No | A positive integer representing how much to transfer. |
| `created` | query | any | No | A filter on the list, based on the object `created` field. The value can be a string with an integer Unix timestamp, or it can be a dictionary with a number of different query options. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: canceled, failed, pending... | No | Only return top-ups that have the given status. One of `canceled`, `failed`, `pending` or `succeeded`. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

