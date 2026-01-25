# GET /accounts/{account_id}/zt_risk_scoring/{user_id}

**Resource:** [Zero Trust Risk Scoring](../resources/Zero-Trust-Risk-Scoring.md)
**Get risk event/score information for a specific user**
**Operation ID:** `dlp-risk-score-summary-get-for-user`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `user_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Risk events. |
| 4XX | Failed to get risk events. |

## Security

- **api_email**
- **api_key**
- **api_token**
