# GET /v1/treasury/transactions

**Resource:** [treasury](../resources/treasury.md)
**List all Transactions**
**Operation ID:** `GetTreasuryTransactions`

<p>Retrieves a list of Transaction objects.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | any | No | Only return Transactions that were created during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `financial_account` | query | string | Yes | Returns objects associated with this FinancialAccount. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `order_by` | query | enum: created, posted_at | No | The results are in reverse chronological order by `created` or `posted_at`. The default is `created`. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: open, posted, void | No | Only return Transactions that have the given status: `open`, `posted`, or `void`. |
| `status_transitions` | query | object | No | A filter for the `status_transitions.posted_at` timestamp. When using this filter, `status=posted` and `order_by=posted_at` must also be specified. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

