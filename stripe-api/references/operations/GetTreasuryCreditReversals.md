# GET /v1/treasury/credit_reversals

**Resource:** [treasury](../resources/treasury.md)
**List all CreditReversals**
**Operation ID:** `GetTreasuryCreditReversals`

<p>Returns a list of CreditReversals.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `financial_account` | query | string | Yes | Returns objects associated with this FinancialAccount. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `received_credit` | query | string | No | Only return CreditReversals for the ReceivedCredit ID. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: canceled, posted, processing | No | Only return CreditReversals for a given status. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

