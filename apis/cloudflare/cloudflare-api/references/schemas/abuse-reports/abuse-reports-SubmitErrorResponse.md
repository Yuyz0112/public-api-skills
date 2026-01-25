# abuse-reports_SubmitErrorResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error_code` | [abuse-reports_ErrorCode](abuse-reports-ErrorCode.md) | Yes |  |
| `msg` | string | Yes | The error message for the error |
| `request` | object | Yes |  |
| `result` | string | Yes | The result should be 'error' for successful response |

## Nested Fields

### `request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `act` | [abuse-reports_SubmissionReportType](abuse-reports-SubmissionReportType.md) | Yes |  |

