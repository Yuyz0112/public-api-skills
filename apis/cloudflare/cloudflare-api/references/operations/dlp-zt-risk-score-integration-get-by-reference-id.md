# GET /accounts/{account_id}/zt_risk_scoring/integrations/reference_id/{reference_id}

**Resource:** [Zero Trust Risk Scoring Integrations](../resources/Zero-Trust-Risk-Scoring-Integrations.md)
**Get risk score integration by reference id.**
**Operation ID:** `dlp-zt-risk-score-integration-get-by-reference-id`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `reference_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get response. |
| 4XX | Get failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
