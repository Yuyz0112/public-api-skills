# GET /zones/{zone_id}/security-center/insights

**Resource:** [Security Center Insights](../resources/Security-Center-Insights.md)
**Get Zone Security Center Insights**
**Operation ID:** `get-zone-security-center-insights`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | security-center_identifier | Yes |  |
| `dismissed` | query | security-center_dismissed | No |  |
| `issue_class` | query | security-center_issueClasses | No |  |
| `issue_type` | query | security-center_issueTypes | No |  |
| `product` | query | security-center_products | No |  |
| `severity` | query | security-center_severityQueryParam | No |  |
| `subject` | query | security-center_subjects | No |  |
| `issue_class~neq` | query | security-center_issueClasses | No |  |
| `issue_type~neq` | query | security-center_issueTypes | No |  |
| `product~neq` | query | security-center_products | No |  |
| `severity~neq` | query | security-center_severityQueryParam | No |  |
| `subject~neq` | query | security-center_subjects | No |  |
| `page` | query | any | No |  |
| `per_page` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 4XX | Client Error |

## Security

- **api_email**
- **api_key**
- **api_token**
