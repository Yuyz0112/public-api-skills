# POST /v1/treasury/financial_accounts/{financial_account}/close

**Resource:** [treasury](../resources/treasury.md)
**Close a FinancialAccount**
**Operation ID:** `PostTreasuryFinancialAccountsFinancialAccountClose`

<p>Closes a FinancialAccount. A FinancialAccount can only be closed if it has a zero balance, has no pending InboundTransfers, and has canceled all attached Issuing cards.</p>

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

[treasury.financial_account](../schemas/treasury-financial/treasury-financial-account.md)

