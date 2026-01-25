# GET /accounts/{account_id}/abuse-reports

**Resource:** [tseng-abuse-complaint-processor_other](../resources/tseng-abuse-complaint-processor-other.md)
**List abuse reports**
**Operation ID:** `ListAbuseReports`

List the abuse reports for a given account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Cloudflare Account ID |
| `page` | query | integer | No | Where in pagination to start listing abuse reports |
| `per_page` | query | integer | No | How many abuse reports per page to list |
| `sort` | query | string | No | A property to sort by, followed by the order (id, cdate, domain, type, status) |
| `domain` | query | string | No | Filter by domain name related to the abuse report |
| `created_before` | query | string | No | Returns reports created before the specified date |
| `created_after` | query | string | No | Returns reports created after the specified date |
| `status` | query | abuse-reports_ReportStatus | No | Filter by the status of the report. |
| `type` | query | abuse-reports_ReportType | No | Filter by the type of the report. |
| `mitigation_status` | query | abuse-reports_MitigationStatus | No | Filter reports that have any mitigations in the given status. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Abuse report list successful |
| 500 | Failed to retrieve abuse reports |

## Security

- **api_token**
