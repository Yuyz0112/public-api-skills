# CreateIssueSourceRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Board, Project, Filter | Yes | The issue source type. This must be "Board", "Project" or "Filter". |
| `value` | integer (int64) | Yes | The issue source value. This must be a board ID if the type is "Board", a project ID if the type is "Project" or a filter ID if the type is "Filter". |

