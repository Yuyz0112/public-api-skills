# pull-request-event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes |  |
| `number` | integer | Yes |  |
| `pull_request` | [pull-request-minimal](pull-request-minimal.md) | Yes |  |
| `assignee` | [simple-user](simple-user.md) | No |  |
| `assignees` | simple-user[] | No |  |
| `label` | [label](label.md) | No |  |
| `labels` | label[] | No |  |

