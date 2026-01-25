# abuse-reports_MitigationSummary

A summary of the mitigations related to this report.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accepted_url_count` | integer | Yes | How many of the reported URLs were confirmed as abusive. |
| `active_count` | integer | Yes | How many mitigations are active. |
| `external_host_notified` | boolean | Yes | Whether the report has been forwarded to an external hosting provider. |
| `in_review_count` | integer | Yes | How many mitigations are under review. |
| `pending_count` | integer | Yes | How many mitigations are pending their effective date. |

