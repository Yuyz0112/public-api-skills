# POST /v1/customers/{customer}/balance_transactions/{transaction}

**Resource:** [customers](../resources/customers.md)
**Update a customer credit balance transaction**
**Operation ID:** `PostCustomersCustomerBalanceTransactionsTransaction`

<p>Most credit balance transaction fields are immutable, but you may update its <code>description</code> and <code>metadata</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
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

