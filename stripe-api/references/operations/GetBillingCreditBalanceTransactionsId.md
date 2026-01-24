# GET /v1/billing/credit_balance_transactions/{id}

**Resource:** [billing](../resources/billing.md)
**Retrieve a credit balance transaction**
**Operation ID:** `GetBillingCreditBalanceTransactionsId`

<p>Retrieves a credit balance transaction.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | Unique identifier for the object. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.credit_balance_transaction](../schemas/billing-credit/billing-credit-balance-transaction.md)

