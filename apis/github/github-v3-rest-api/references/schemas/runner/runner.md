# runner

A self hosted runner

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the runner. |
| `runner_group_id` | integer | No | The ID of the runner group. |
| `name` | string | Yes | The name of the runner. |
| `os` | string | Yes | The Operating System of the runner. |
| `status` | string | Yes | The status of the runner. |
| `busy` | boolean | Yes |  |
| `labels` | runner-label[] | Yes |  |
| `ephemeral` | boolean | No |  |

