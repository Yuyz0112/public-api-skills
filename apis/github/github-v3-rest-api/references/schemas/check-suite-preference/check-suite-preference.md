# check-suite-preference

Check suite configuration preferences for a repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `preferences` | object | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |

## Nested Fields

### `preferences`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auto_trigger_checks` | object[] | No |  |

#### `preferences.auto_trigger_checks`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `app_id` | integer | Yes |  |
| `setting` | boolean | Yes |  |

