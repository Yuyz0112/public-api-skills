# PUT /accounts/{account_id}/zt_risk_scoring/behaviors

**Resource:** [Zero Trust Risk Scoring](../resources/Zero-Trust-Risk-Scoring.md)
**Update configuration for risk behaviors**
**Operation ID:** `dlp-risk-score-behaviors-put`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

Behaviors.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_UpdateBehaviors](../schemas/dlp/dlp-UpdateBehaviors.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Dataset created successfully. |
| 4XX | Dataset creation failed. |

## Security

- **api_email**
- **api_key**
- **api_token**
