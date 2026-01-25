# GetPlanResponseForPage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The plan ID. |
| `issueSources` | GetIssueSourceResponse[] | No | The issue sources included in the plan. |
| `name` | string | Yes | The plan name. |
| `scenarioId` | string | Yes | Default scenario ID. |
| `status` | enum: Active, Trashed, Archived | Yes | The plan status. This is "Active", "Trashed" or "Archived". |

