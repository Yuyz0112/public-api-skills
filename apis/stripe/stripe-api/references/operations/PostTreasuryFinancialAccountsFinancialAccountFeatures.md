# POST /v1/treasury/financial_accounts/{financial_account}/features

**Resource:** [treasury](../resources/treasury.md)
**Update FinancialAccount Features**
**Operation ID:** `PostTreasuryFinancialAccountsFinancialAccountFeatures`

<p>Updates the Features associated with a FinancialAccount.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

