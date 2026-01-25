# GET /v1/subscriptions

**Resource:** [subscriptions](../resources/subscriptions.md)
**List subscriptions**
**Operation ID:** `GetSubscriptions`

<p>By default, returns a list of subscriptions that have not been canceled. In order to list canceled subscriptions, specify <code>status=canceled</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `automatic_tax` | query | object | No | Filter subscriptions by their automatic tax settings. |
| `collection_method` | query | enum: charge_automatically, send_invoice | No | The collection method of the subscriptions to retrieve. Either `charge_automatically` or `send_invoice`. |
| `created` | query | any | No | Only return subscriptions that were created during the given date interval. |
| `current_period_end` | query | any | No | Only return subscriptions whose minimum item current_period_end falls within the given date interval. |
| `current_period_start` | query | any | No | Only return subscriptions whose maximum item current_period_start falls within the given date interval. |
| `customer` | query | string | No | The ID of the customer whose subscriptions you're retrieving. |
| `customer_account` | query | string | No | The ID of the account representing the customer whose subscriptions you're retrieving. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `price` | query | string | No | Filter for subscriptions that contain this recurring price ID. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: active, all, canceled... | No | The status of the subscriptions to retrieve. Passing in a value of `canceled` will return all canceled subscriptions, including those belonging to deleted customers. Pass `ended` to find subscriptions that are canceled and subscriptions that are expired due to [incomplete payment](https://docs.stripe.com/billing/subscriptions/overview#subscription-statuses). Passing in a value of `all` will return subscriptions of all statuses. If no value is supplied, all subscriptions that have not been canceled are returned. |
| `test_clock` | query | string | No | Filter for subscriptions that are associated with the specified test clock. The response will not include subscriptions with test clocks if this and the customer parameter is not set. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

