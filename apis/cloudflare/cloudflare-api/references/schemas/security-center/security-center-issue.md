# security-center_issue

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dismissed` | boolean | No |  |
| `id` | string | No |  |
| `issue_class` | [security-center_issueClass](security-center-issueClass.md) | No |  |
| `issue_type` | [security-center_issueType](security-center-issueType.md) | No |  |
| `payload` | object | No |  |
| `resolve_link` | string | No |  |
| `resolve_text` | string | No |  |
| `severity` | enum: Low, Moderate, Critical | No |  |
| `since` | string (date-time) | No |  |
| `subject` | [security-center_subject](security-center-subject.md) | No |  |
| `timestamp` | string (date-time) | No |  |

## Nested Fields

### `payload`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `detection_method` | string | No | Method used to detect insight |
| `zone_tag` | string | No |  |

