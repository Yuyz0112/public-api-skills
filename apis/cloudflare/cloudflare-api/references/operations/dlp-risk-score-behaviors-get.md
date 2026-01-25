# GET /accounts/{account_id}/zt_risk_scoring/behaviors

**Resource:** [Zero Trust Risk Scoring](../resources/Zero-Trust-Risk-Scoring.md)
**Get all behaviors and associated configuration**
**Operation ID:** `dlp-risk-score-behaviors-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Risk scoring behaviors. |
| 4XX | Failed to get risk scoring behaviors. |

## Security

- **api_email**
- **api_key**
- **api_token**
