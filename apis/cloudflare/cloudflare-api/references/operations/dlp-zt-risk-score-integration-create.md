# POST /accounts/{account_id}/zt_risk_scoring/integrations

**Resource:** [Zero Trust Risk Scoring Integrations](../resources/Zero-Trust-Risk-Scoring-Integrations.md)
**Create new risk score integration.**
**Operation ID:** `dlp-zt-risk-score-integration-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_CreateIntegrationBody](../schemas/dlp/dlp-CreateIntegrationBody.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create response. |
| 4XX | Create failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
