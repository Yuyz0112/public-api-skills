# PUT /accounts/{account_id}/zt_risk_scoring/integrations/{integration_id}

**Resource:** [Zero Trust Risk Scoring Integrations](../resources/Zero-Trust-Risk-Scoring-Integrations.md)
**Update a risk score integration.**
**Operation ID:** `dlp-zt-risk-score-integration-update`

Overwrite the reference_id, tenant_url, and active values with the ones provided.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `integration_id` | path | string (uuid) | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_UpdateIntegrationBody](../schemas/dlp/dlp-UpdateIntegrationBody.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update response. |
| 4XX | Update failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
