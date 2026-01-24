# GET /v1/billing/credit_balance_summary

**Resource:** [billing](../resources/billing.md)
**Retrieve the credit balance summary for a customer**
**Operation ID:** `GetBillingCreditBalanceSummary`

<p>Retrieves the credit balance summary for a customer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | query | string | No | The customer whose credit balance summary you're retrieving. |
| `customer_account` | query | string | No | The account representing the customer whose credit balance summary you're retrieving. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `filter` | query | object | Yes | The filter criteria for the credit balance summary. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.credit_balance_summary](../schemas/billing-credit/billing-credit-balance-summary.md)

