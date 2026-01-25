# repository-rule-update

Only allow users with bypass permission to update matching refs.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: update | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `update_allows_fetch_and_merge` | boolean | Yes | Branch can pull changes from its upstream repository |

