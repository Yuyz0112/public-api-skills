# GET /v1/customers/{customer}/cash_balance_transactions/{transaction}

**Resource:** [customers](../resources/customers.md)
**Retrieve a cash balance transaction**
**Operation ID:** `GetCustomersCustomerCashBalanceTransactionsTransaction`

<p>Retrieves a specific cash balance transaction, which updated the customer’s <a href="/docs/payments/customer-balance">cash balance</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `transaction` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[customer_cash_balance_transaction](../schemas/customer/customer-cash-balance-transaction.md)

