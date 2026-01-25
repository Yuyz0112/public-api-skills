# PUT /zones/{zone_id}/security-center/insights/{issue_id}/dismiss

**Resource:** [Security Center Insights](../resources/Security-Center-Insights.md)
**Archive Zone Security Center Insight**
**Operation ID:** `archive-zone-security-center-insight`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | security-center_identifier | Yes |  |
| `issue_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 4XX | Client Error |

## Security

- **api_email**
- **api_key**
- **api_token**
