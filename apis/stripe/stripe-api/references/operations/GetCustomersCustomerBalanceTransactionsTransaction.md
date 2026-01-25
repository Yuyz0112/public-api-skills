# GET /v1/customers/{customer}/balance_transactions/{transaction}

**Resource:** [customers](../resources/customers.md)
**Retrieve a customer balance transaction**
**Operation ID:** `GetCustomersCustomerBalanceTransactionsTransaction`

<p>Retrieves a specific customer balance transaction that updated the customer’s <a href="/docs/billing/customer/balance">balances</a>.</p>

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

[customer_balance_transaction](../schemas/customer/customer-balance-transaction.md)

