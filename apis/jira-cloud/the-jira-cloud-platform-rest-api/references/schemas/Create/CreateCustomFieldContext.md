# CreateCustomFieldContext

The details of a created custom field context.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the context. |
| `id` | string | No | The ID of the context. |
| `issueTypeIds` | string[] | No | The list of issue types IDs for the context. If the list is empty, the context refers to all issue types. |
| `name` | string | Yes | The name of the context. |
| `projectIds` | string[] | No | The list of project IDs associated with the context. If the list is empty, the context is global. |

