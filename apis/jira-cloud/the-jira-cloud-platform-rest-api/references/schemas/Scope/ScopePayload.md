# ScopePayload

The payload for creating a scope. Defines if a project is team-managed project or company-managed project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: GLOBAL, PROJECT | No | The type of the scope. Use `GLOBAL` or empty for company-managed project, and `PROJECT` for team-managed project |

