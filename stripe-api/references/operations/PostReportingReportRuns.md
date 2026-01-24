# POST /v1/reporting/report_runs

**Resource:** [reporting](../resources/reporting.md)
**Create a Report Run**
**Operation ID:** `PostReportingReportRuns`

<p>Creates a new object and begin running the report. (Certain report types require a <a href="https://stripe.com/docs/keys#test-live-modes">live-mode API key</a>.)</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[reporting.report_run](../schemas/reporting-report/reporting-report-run.md)

