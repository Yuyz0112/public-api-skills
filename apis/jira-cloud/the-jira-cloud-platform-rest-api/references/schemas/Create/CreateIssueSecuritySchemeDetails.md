# CreateIssueSecuritySchemeDetails

Issue security scheme and it's details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the issue security scheme. |
| `levels` | SecuritySchemeLevelBean[] | No | The list of scheme levels which should be added to the security scheme. |
| `name` | string | Yes | The name of the issue security scheme. Must be unique (case-insensitive). |

