# GetTeamResponseForPage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The team ID. |
| `name` | string | No | The team name. This is returned if the type is "PlanOnly". |
| `type` | enum: PlanOnly, Atlassian | Yes | The team type. This is "PlanOnly" or "Atlassian". |

