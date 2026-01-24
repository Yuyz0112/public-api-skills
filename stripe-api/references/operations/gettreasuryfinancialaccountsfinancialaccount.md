# GET /v1/treasury/financial_accounts/{financial_account}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a FinancialAccount**
**Operation ID:** `GetTreasuryFinancialAccountsFinancialAccount`

<p>Retrieves the details of a FinancialAccount.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `financial_account` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.financial_account](../schemas/treasury-financial/treasury-financial-account.md)

