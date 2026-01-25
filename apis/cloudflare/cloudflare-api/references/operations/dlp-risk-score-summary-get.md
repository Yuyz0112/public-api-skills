# GET /accounts/{account_id}/zt_risk_scoring/summary

**Resource:** [Zero Trust Risk Scoring](../resources/Zero-Trust-Risk-Scoring.md)
**Get risk score info for all users in the account**
**Operation ID:** `dlp-risk-score-summary-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Risk score for all users in the account. |
| 4XX | Failed to get risk scores. |

## Security

- **api_email**
- **api_key**
- **api_token**
