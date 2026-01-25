# GET /v1/billing/credit_balance_transactions

**Resource:** [billing](../resources/billing.md)
**List credit balance transactions**
**Operation ID:** `GetBillingCreditBalanceTransactions`

<p>Retrieve a list of credit balance transactions.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `credit_grant` | query | string | No | The credit grant for which to fetch credit balance transactions. |
| `customer` | query | string | No | The customer whose credit balance transactions you're retrieving. |
| `customer_account` | query | string | No | The account representing the customer whose credit balance transactions you're retrieving. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

