# GET /v1/customers

**Resource:** [customers](../resources/customers.md)
**List all customers**
**Operation ID:** `GetCustomers`

<p>Returns a list of your customers. The customers are returned sorted by creation date, with the most recent customers appearing first.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | any | No | Only return customers that were created during the given date interval. |
| `email` | query | string | No | A case-sensitive filter on the list based on the customer's `email` field. The value must be a string. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `test_clock` | query | string | No | Provides a list of customers that are associated with the specified test clock. The response will not include customers with test clocks if this parameter is not set. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

