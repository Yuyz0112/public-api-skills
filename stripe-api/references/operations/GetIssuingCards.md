# GET /v1/issuing/cards

**Resource:** [issuing](../resources/issuing.md)
**List all cards**
**Operation ID:** `GetIssuingCards`

<p>Returns a list of Issuing <code>Card</code> objects. The objects are sorted in descending order by creation date, with the most recently created object appearing first.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cardholder` | query | string | No | Only return cards belonging to the Cardholder with the provided ID. |
| `created` | query | any | No | Only return cards that were issued during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `exp_month` | query | integer | No | Only return cards that have the given expiration month. |
| `exp_year` | query | integer | No | Only return cards that have the given expiration year. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `last4` | query | string | No | Only return cards that have the given last four digits. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `personalization_design` | query | string | No |  |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: active, canceled, inactive | No | Only return cards that have the given status. One of `active`, `inactive`, or `canceled`. |
| `type` | query | enum: physical, virtual | No | Only return cards that have the given type. One of `virtual` or `physical`. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

