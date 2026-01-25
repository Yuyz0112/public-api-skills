# GET /accounts/{account_id}/zt_risk_scoring/integrations

**Resource:** [Zero Trust Risk Scoring Integrations](../resources/Zero-Trust-Risk-Scoring-Integrations.md)
**List all risk score integrations for the account.**
**Operation ID:** `dlp-zt-risk-score-integration-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List response. |
| 4XX | List failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
