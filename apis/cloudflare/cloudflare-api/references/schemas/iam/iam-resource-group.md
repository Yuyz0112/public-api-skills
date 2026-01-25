# iam_resource_group

A group of scoped resources.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Identifier of the resource group. |
| `meta` | object | No | Attributes associated to the resource group. |
| `name` | string | No | Name of the resource group. |
| `scope` | iam_scope[] | Yes | The scope associated to the resource group |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | No |  |
| `value` | string | No |  |

