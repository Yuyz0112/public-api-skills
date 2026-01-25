# repository-ruleset-conditions-repository-id-target

Parameters for a repository ID condition

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository_id` | object | Yes |  |

## Nested Fields

### `repository_id`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository_ids` | integer[] | No | The repository IDs that the ruleset applies to. One of these IDs must match for the condition to pass. |

