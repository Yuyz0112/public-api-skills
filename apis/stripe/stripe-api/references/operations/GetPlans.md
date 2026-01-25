# GET /v1/plans

**Resource:** [plans](../resources/plans.md)
**List all plans**
**Operation ID:** `GetPlans`

<p>Returns a list of your plans.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `active` | query | boolean | No | Only return plans that are active or inactive (e.g., pass `false` to list all inactive plans). |
| `created` | query | any | No | A filter on the list, based on the object `created` field. The value can be a string with an integer Unix timestamp, or it can be a dictionary with a number of different query options. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `product` | query | string | No | Only return plans for the given product. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

