# GET /accounts/{account_id}/abuse-reports/{report_id}/mitigations

**Resource:** [tseng-abuse-complaint-processor_other](../resources/tseng-abuse-complaint-processor-other.md)
**List abuse report mitigations**
**Operation ID:** `ListMitigations`

List mitigations done to remediate the abuse report.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Cloudflare Account ID |
| `report_id` | path | string | Yes | Abuse Report ID |
| `page` | query | integer | No | Where in pagination to start listing abuse reports |
| `per_page` | query | integer | No | How many abuse reports per page to list |
| `sort` | query | enum: type,asc, type,desc, effective_date,asc... | No | A property to sort by, followed by the order |
| `type` | query | abuse-reports_MitigationType | No | Filter by the type of mitigation. This filter parameter can be specified multiple times to include multiple types of mitigations in the result set, e.g. ?type=rate_limit_cache&type=legal_block. |
| `effective_before` | query | string | No | Returns mitigations that were dispatched before the given date |
| `effective_after` | query | string | No | Returns mitigation that were dispatched after the given date |
| `status` | query | abuse-reports_MitigationStatus | No | Filter by the status of the mitigation. |
| `entity_type` | query | abuse-reports_MitigatedEntityType | No | Filter by the type of entity the mitigation impacts. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List abuse report mitigations successful |
| 500 | Failed to list abuse report mitigations |

## Security

- **api_token**
