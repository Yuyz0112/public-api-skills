# abuse-reports_MitigationListItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `effective_date` | string | Yes | Date when the mitigation will become active. Time in RFC 3339 format (https://www.rfc-editor.org/rfc/rfc3339.html) |
| `entity_id` | string | Yes |  |
| `entity_type` | [abuse-reports_MitigatedEntityType](abuse-reports-MitigatedEntityType.md) | Yes |  |
| `id` | string | Yes | ID of remediation. |
| `status` | [abuse-reports_MitigationStatus](abuse-reports-MitigationStatus.md) | Yes |  |
| `type` | [abuse-reports_MitigationType](abuse-reports-MitigationType.md) | Yes |  |

