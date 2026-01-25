# bot-management_feedback_report

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No |  |
| `description` | string | Yes |  |
| `expression` | string | Yes | Wirefilter expression describing the traffic being reported. |
| `first_request_seen_at` | string (date-time) | Yes |  |
| `last_request_seen_at` | string (date-time) | Yes |  |
| `requests` | integer (int64) | Yes |  |
| `requests_by_attribute` | [bot-management_requests_by_attribute](bot-management-requests-by-attribute.md) | Yes |  |
| `requests_by_score` | [bot-management_requests_by_score](bot-management-requests-by-score.md) | Yes |  |
| `requests_by_score_src` | [bot-management_requests_by_score_src](bot-management-requests-by-score-src.md) | Yes |  |
| `subtype` | string | No |  |
| `type` | [bot-management_feedback_type](bot-management-feedback-type.md) | Yes |  |

