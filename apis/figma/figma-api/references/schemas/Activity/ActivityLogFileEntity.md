# ActivityLogFileEntity

A Figma Design or FigJam file

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: file | Yes | The type of entity. |
| `key` | string | Yes | Unique identifier of the file. |
| `name` | string | Yes | Name of the file. |
| `editor_type` | enum: figma, figjam | Yes | Indicates if the object is a file on Figma Design or FigJam. |
| `link_access` | [LinkAccess](LinkAccess.md) | Yes |  |
| `proto_link_access` | enum: view, org_view, inherit | Yes | Access policy for users who have the link to the file's prototype. |

