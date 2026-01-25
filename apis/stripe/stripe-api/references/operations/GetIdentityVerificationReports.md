# GET /v1/identity/verification_reports

**Resource:** [identity](../resources/identity.md)
**List VerificationReports**
**Operation ID:** `GetIdentityVerificationReports`

<p>List all verification reports.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_reference_id` | query | string | No | A string to reference this user. This can be a customer ID, a session ID, or similar, and can be used to reconcile this verification with your internal systems. |
| `created` | query | any | No | Only return VerificationReports that were created during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `type` | query | enum: document, id_number | No | Only return VerificationReports of this type |
| `verification_session` | query | string | No | Only return VerificationReports created by this VerificationSession ID. It is allowed to provide a VerificationIntent ID. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

