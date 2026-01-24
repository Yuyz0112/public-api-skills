# GET /v1/identity/verification_sessions

**Resource:** [identity](../resources/identity.md)
**List VerificationSessions**
**Operation ID:** `GetIdentityVerificationSessions`

<p>Returns a list of VerificationSessions</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_reference_id` | query | string | No | A string to reference this user. This can be a customer ID, a session ID, or similar, and can be used to reconcile this verification with your internal systems. |
| `created` | query | any | No | Only return VerificationSessions that were created during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `related_customer` | query | string | No | Customer ID |
| `related_customer_account` | query | string | No | The ID of the Account representing a customer. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: canceled, processing, requires_input... | No | Only return VerificationSessions with this status. [Learn more about the lifecycle of sessions](https://docs.stripe.com/identity/how-sessions-work). |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

