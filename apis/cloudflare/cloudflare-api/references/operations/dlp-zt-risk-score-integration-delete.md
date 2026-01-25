# DELETE /accounts/{account_id}/zt_risk_scoring/integrations/{integration_id}

**Resource:** [Zero Trust Risk Scoring Integrations](../resources/Zero-Trust-Risk-Scoring-Integrations.md)
**Delete a risk score integration.**
**Operation ID:** `dlp-zt-risk-score-integration-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `integration_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete response. |
| 4XX | Delete failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
