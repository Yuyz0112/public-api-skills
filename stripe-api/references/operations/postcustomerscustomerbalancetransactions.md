# POST /v1/customers/{customer}/balance_transactions

**Resource:** [customers](../resources/customers.md)
**Create a customer balance transaction**
**Operation ID:** `PostCustomersCustomerBalanceTransactions`

<p>Creates an immutable transaction that updates the customer’s credit <a href="/docs/billing/customer/balance">balance</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[customer_balance_transaction](../schemas/customer/customer-balance-transaction.md)

