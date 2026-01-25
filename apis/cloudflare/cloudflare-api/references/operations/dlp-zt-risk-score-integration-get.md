# GET /accounts/{account_id}/zt_risk_scoring/integrations/{integration_id}

**Resource:** [Zero Trust Risk Scoring Integrations](../resources/Zero-Trust-Risk-Scoring-Integrations.md)
**Get risk score integration by id.**
**Operation ID:** `dlp-zt-risk-score-integration-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `integration_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get response. |
| 4XX | Get failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
