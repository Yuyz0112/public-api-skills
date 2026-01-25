# Style

A set of properties that can be applied to nodes and published. Styles for a property can be created in the corresponding property's panel while editing a file.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The key of the style |
| `name` | string | Yes | Name of the style |
| `description` | string | Yes | Description of the style |
| `remote` | boolean | Yes | Whether this style is a remote style that doesn't live in this file |
| `styleType` | [StyleType](StyleType.md) | Yes |  |

