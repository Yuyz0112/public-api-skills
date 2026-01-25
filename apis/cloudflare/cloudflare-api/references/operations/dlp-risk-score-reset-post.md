# POST /accounts/{account_id}/zt_risk_scoring/{user_id}/reset

**Resource:** [Zero Trust Risk Scoring](../resources/Zero-Trust-Risk-Scoring.md)
**Clear the risk score for a particular user**
**Operation ID:** `dlp-risk-score-reset-post`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `user_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset created successfully. |
| 4XX | Dataset creation failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
