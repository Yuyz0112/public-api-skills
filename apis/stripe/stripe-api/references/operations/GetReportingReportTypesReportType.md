# GET /v1/reporting/report_types/{report_type}

**Resource:** [reporting](../resources/reporting.md)
**Retrieve a Report Type**
**Operation ID:** `GetReportingReportTypesReportType`

<p>Retrieves the details of a Report Type. (Certain report types require a <a href="https://stripe.com/docs/keys#test-live-modes">live-mode API key</a>.)</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `report_type` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[reporting.report_type](../schemas/reporting-report/reporting-report-type.md)

