# GET /v1/reporting/report_types

**Resource:** [reporting](../resources/reporting.md)
**List all Report Types**
**Operation ID:** `GetReportingReportTypes`

<p>Returns a full list of Report Types.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

