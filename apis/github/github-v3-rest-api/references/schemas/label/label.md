# label

Color-coded labels help you categorize and filter your issues (just like labels in Gmail).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier for the label. |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the label |
| `name` | string | Yes | The name of the label. |
| `description` | string | Yes | Optional description of the label, such as its purpose. |
| `color` | string | Yes | 6-character hex code, without the leading #, identifying the color |
| `default` | boolean | Yes | Whether this label comes by default in a new repository. |

