# GET /accounts/{account_id}/brand-protection/matches/download

**Resource:** [domain_search](../resources/domain-search.md)
**Download matches for string queries by ID**
**Operation ID:** `get--accounts-{account_id}-brand-protection-matches-download`

Return matches as CSV for string queries based on ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string | No |  |
| `offset` | query | integer | No |  |
| `limit` | query | integer | No |  |
| `include_domain_id` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 422 | (reference) |
| default | (reference) |

**Success Response Schema:**

[brand-protection-api_QueryMatch](../schemas/brand-protection-api/brand-protection-api-QueryMatch.md)

## Security

- **api_token**
