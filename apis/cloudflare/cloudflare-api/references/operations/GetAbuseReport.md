# GET /accounts/{account_id}/abuse-reports/{report_param}

**Resource:** [tseng-abuse-complaint-processor_other](../resources/tseng-abuse-complaint-processor-other.md)
**Abuse Report Details**
**Operation ID:** `GetAbuseReport`

Retrieve the details of an abuse report.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Cloudflare Account ID |
| `report_param` | path | string | Yes | Identifier of the abuse report |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Report submitted successfully |
| 400 | Report submitted with an error |
| 500 | Report submitted with an error |

## Security

- **api_token**
