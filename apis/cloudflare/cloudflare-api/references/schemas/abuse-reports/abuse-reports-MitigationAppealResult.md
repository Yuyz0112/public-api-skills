# abuse-reports_MitigationAppealResult

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | abuse-reports_Message[] | No |  |
| `messages` | abuse-reports_Message[] | No |  |
| `result` | abuse-reports_MitigationListItem[] | No |  |
| `result_info` | object | Yes |  |
| `success` | boolean | Yes |  |

## Nested Fields

### `result_info`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | Yes |  |
| `page` | number | Yes |  |
| `per_page` | number | Yes |  |
| `total_count` | number | Yes |  |
| `total_pages` | number | Yes |  |

