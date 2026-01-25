# abuse-reports_AbuseReport

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cdate` | string | Yes | Creation date of report. Time in RFC 3339 format (https://www.rfc-editor.org/rfc/rfc3339.html) |
| `domain` | string | Yes | Domain that relates to the report. |
| `id` | string | Yes | Public facing ID of abuse report, aka abuse_rand. |
| `justification` | string | No | Justification for the report. |
| `mitigation_summary` | [abuse-reports_MitigationSummary](abuse-reports-MitigationSummary.md) | Yes |  |
| `original_work` | string | No | Original work / Targeted brand in the alleged abuse. |
| `status` | [abuse-reports_ReportStatus](abuse-reports-ReportStatus.md) | Yes |  |
| `submitter` | [abuse-reports_SubmitterDetails](abuse-reports-SubmitterDetails.md) | No |  |
| `type` | [abuse-reports_ReportType](abuse-reports-ReportType.md) | Yes |  |
| `urls` | string[] | No |  |

