# GET /v1/treasury/financial_accounts

**Resource:** [treasury](../resources/treasury.md)
**List all FinancialAccounts**
**Operation ID:** `GetTreasuryFinancialAccounts`

<p>Returns a list of FinancialAccounts.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | any | No | Only return FinancialAccounts that were created during the given date interval. |
| `ending_before` | query | string | No | An object ID cursor for use in pagination. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit ranging from 1 to 100 (defaults to 10). |
| `starting_after` | query | string | No | An object ID cursor for use in pagination. |
| `status` | query | enum: closed, open | No | Only return FinancialAccounts that have the given status: `open` or `closed` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

