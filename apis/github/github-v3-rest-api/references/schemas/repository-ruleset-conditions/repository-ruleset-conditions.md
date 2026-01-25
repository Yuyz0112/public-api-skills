# repository-ruleset-conditions

Parameters for a repository ruleset ref name condition

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref_name` | object | No |  |

## Nested Fields

### `ref_name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `include` | string[] | No | Array of ref names or patterns to include. One of these patterns must match for the condition to pass. Also accepts `~DEFAULT_BRANCH` to include the default branch or `~ALL` to include all branches. |
| `exclude` | string[] | No | Array of ref names or patterns to exclude. The condition will not pass if any of these patterns match. |

