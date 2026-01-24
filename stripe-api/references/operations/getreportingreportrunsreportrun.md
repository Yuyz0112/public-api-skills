# GET /v1/reporting/report_runs/{report_run}

**Resource:** [reporting](../resources/reporting.md)
**Retrieve a Report Run**
**Operation ID:** `GetReportingReportRunsReportRun`

<p>Retrieves the details of an existing Report Run.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `report_run` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[reporting.report_run](../schemas/reporting-report/reporting-report-run.md)

