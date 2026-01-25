# iam_create-scope

A scope is a combination of scope objects which provides additional context.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | [iam_create_resource_group_scope_scope_key](iam-create-resource-group-scope-scope-key.md) | Yes |  |
| `objects` | iam_create_resource_group_scope_scope_object[] | Yes | A list of scope objects for additional context. The number of Scope objects should not be zero. |

