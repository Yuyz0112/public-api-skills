# GET /accounts/{account_id}/security-center/insights/class

**Resource:** [Security Center Insights](../resources/Security-Center-Insights.md)
**Get Security Center Insight Counts by Class**
**Operation ID:** `get-security-center-insight-counts-by-class`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | security-center_identifier | Yes |  |
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

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 4XX | Client Error |

**Success Response Schema:**

[security-center_valueCountsResponse](../schemas/security-center/security-center-valueCountsResponse.md)

## Security

- **api_email**
- **api_key**
- **api_token**
