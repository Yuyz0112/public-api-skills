# DeleteRulesRequest

A response from deleting user-specified stream filtering rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `delete` | object | Yes | IDs and values of all deleted user-specified stream filtering rules. |

## Nested Fields

### `delete`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ids` | RuleId[] | No | IDs of all deleted user-specified stream filtering rules. |
| `values` | RuleValue[] | No | Values of all deleted user-specified stream filtering rules. |

