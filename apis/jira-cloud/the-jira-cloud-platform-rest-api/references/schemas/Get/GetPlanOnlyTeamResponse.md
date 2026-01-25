# GetPlanOnlyTeamResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capacity` | number (double) | No | The capacity for the plan-only team. |
| `id` | integer (int64) | Yes | The plan-only team ID. |
| `issueSourceId` | integer (int64) | No | The ID of the issue source for the plan-only team. |
| `memberAccountIds` | string[] | No | The account IDs of the plan-only team members. |
| `name` | string | Yes | The plan-only team name. |
| `planningStyle` | enum: Scrum, Kanban | Yes | The planning style for the plan-only team. This is "Scrum" or "Kanban". |
| `sprintLength` | integer (int64) | No | The sprint length for the plan-only team. |

