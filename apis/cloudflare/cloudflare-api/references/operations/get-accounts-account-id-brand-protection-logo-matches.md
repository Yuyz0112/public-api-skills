# GET /accounts/{account_id}/brand-protection/logo-matches

**Resource:** [logo_match](../resources/logo-match.md)
**Read matches for logo queries by ID**
**Operation ID:** `get--accounts-{account_id}-brand-protection-logo-matches`

Return matches for logo queries based on ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `logo_id` | query | string[] | No |  |
| `offset` | query | string | No |  |
| `limit` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 422 | (reference) |
| default | (reference) |

**Success Response Schema:**

[brand-protection-api_LogoMatch](../schemas/brand-protection-api/brand-protection-api-LogoMatch.md)

## Security

- **api_token**
