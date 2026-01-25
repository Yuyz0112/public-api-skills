# abuse-reports_SubmitReportResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `abuse_rand` | string | Yes | The identifier for the submitted abuse report. |
| `request` | object | Yes |  |
| `result` | string | Yes | The result should be 'success' for successful response |

## Nested Fields

### `request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `act` | [abuse-reports_SubmissionReportType](abuse-reports-SubmissionReportType.md) | Yes |  |

