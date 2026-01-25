# repository-ruleset-conditions-repository-property-target

Parameters for a repository property condition

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository_property` | object | Yes |  |

## Nested Fields

### `repository_property`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `include` | repository-ruleset-conditions-repository-property-spec[] | No | The repository properties and values to include. All of these properties must match for the condition to pass. |
| `exclude` | repository-ruleset-conditions-repository-property-spec[] | No | The repository properties and values to exclude. The condition will not pass if any of these properties match. |

