# GET /v1/billing_portal/configurations

**Resource:** [billing_portal](../resources/billing-portal.md)
**List portal configurations**
**Operation ID:** `GetBillingPortalConfigurations`

<p>Returns a list of configurations that describe the functionality of the customer portal.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `active` | query | boolean | No | Only return configurations that are active or inactive (e.g., pass `true` to only list active configurations). |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `is_default` | query | boolean | No | Only return the default or non-default configurations (e.g., pass `true` to only list the default configuration). |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

