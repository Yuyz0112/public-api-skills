# POST /v1/treasury/financial_accounts

**Resource:** [treasury](../resources/treasury.md)
**Create a FinancialAccount**
**Operation ID:** `PostTreasuryFinancialAccounts`

<p>Creates a new FinancialAccount. Each connected account can have up to three FinancialAccounts by default.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.financial_account](../schemas/treasury-financial/treasury-financial-account.md)

