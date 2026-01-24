# GET /v1/treasury/financial_accounts/{financial_account}/features

**Resource:** [treasury](../resources/treasury.md)
**Retrieve FinancialAccount Features**
**Operation ID:** `GetTreasuryFinancialAccountsFinancialAccountFeatures`

<p>Retrieves Features information associated with the FinancialAccount.</p>

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

[treasury.financial_account_features](../schemas/treasury-financial/treasury-financial-account-features.md)

