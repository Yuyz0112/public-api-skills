# GET /v1/issuing/personalization_designs

**Resource:** [issuing](../resources/issuing.md)
**List all personalization designs**
**Operation ID:** `GetIssuingPersonalizationDesigns`

<p>Returns a list of personalization design objects. The objects are sorted in descending order by creation date, with the most recently created object appearing first.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `lookup_keys` | query | string[] | No | Only return personalization designs with the given lookup keys. |
| `preferences` | query | object | No | Only return personalization designs with the given preferences. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: active, inactive, rejected... | No | Only return personalization designs with the given status. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

