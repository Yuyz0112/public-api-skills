# POST /accounts/{account_id}/abuse-reports/{report_param}

**Resource:** [tseng-abuse-complaint-processor_other](../resources/tseng-abuse-complaint-processor-other.md)
**Submit an abuse report**
**Operation ID:** `SubmitAbuseReport`

Submit the Abuse Report of a particular type

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Cloudflare Account ID |
| `report_param` | path | abuse-reports_SubmissionReportType | Yes | The report type to be submitted. Example: abuse_general |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [abuse-reports_SubmitReportRequest](../schemas/abuse-reports/abuse-reports-SubmitReportRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Report submitted successfully |
| 400 | Report submitted with an error |
| 500 | Report submitted with an error |

**Success Response Schema:**

[abuse-reports_SubmitReportResponse](../schemas/abuse-reports/abuse-reports-SubmitReportResponse.md)

## Security

- **api_token**
