# AddAtlassianTeamRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capacity` | number (double) | No | The capacity for the Atlassian team. |
| `id` | string | Yes | The Atlassian team ID. |
| `issueSourceId` | integer (int64) | No | The ID of the issue source for the Atlassian team. |
| `planningStyle` | enum: Scrum, Kanban | Yes | The planning style for the Atlassian team. This must be "Scrum" or "Kanban". |
| `sprintLength` | integer (int64) | No | The sprint length for the Atlassian team. |

