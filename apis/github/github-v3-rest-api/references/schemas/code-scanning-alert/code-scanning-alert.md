# code-scanning-alert

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `number` | [alert-number](alert-number.md) | Yes |  |
| `created_at` | [alert-created-at](alert-created-at.md) | Yes |  |
| `updated_at` | [alert-updated-at](alert-updated-at.md) | No |  |
| `url` | [alert-url](alert-url.md) | Yes |  |
| `html_url` | [alert-html-url](alert-html-url.md) | Yes |  |
| `instances_url` | [alert-instances-url](alert-instances-url.md) | Yes |  |
| `state` | [code-scanning-alert-state](code-scanning-alert-state.md) | Yes |  |
| `fixed_at` | [alert-fixed-at](alert-fixed-at.md) | No |  |
| `dismissed_by` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `dismissed_at` | [alert-dismissed-at](alert-dismissed-at.md) | Yes |  |
| `dismissed_reason` | [code-scanning-alert-dismissed-reason](code-scanning-alert-dismissed-reason.md) | Yes |  |
| `dismissed_comment` | [code-scanning-alert-dismissed-comment](code-scanning-alert-dismissed-comment.md) | No |  |
| `rule` | [code-scanning-alert-rule](code-scanning-alert-rule.md) | Yes |  |
| `tool` | [code-scanning-analysis-tool](code-scanning-analysis-tool.md) | Yes |  |
| `most_recent_instance` | [code-scanning-alert-instance](code-scanning-alert-instance.md) | Yes |  |
| `dismissal_approved_by` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `assignees` | simple-user[] | No |  |

