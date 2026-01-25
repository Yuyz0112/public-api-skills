# repository-ruleset-conditions-repository-name-target

Parameters for a repository name condition

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository_name` | object | Yes |  |

## Nested Fields

### `repository_name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `include` | string[] | No | Array of repository names or patterns to include. One of these patterns must match for the condition to pass. Also accepts `~ALL` to include all repositories. |
| `exclude` | string[] | No | Array of repository names or patterns to exclude. The condition will not pass if any of these patterns match. |
| `protected` | boolean | No | Whether renaming of target repositories is prevented. |

