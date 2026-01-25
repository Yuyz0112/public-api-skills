# GetSchedulingResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dependencies` | enum: Sequential, Concurrent | Yes | The dependencies for the plan. This is "Sequential" or "Concurrent". |
| `endDate` | any | Yes | The end date field for the plan. |
| `estimation` | enum: StoryPoints, Days, Hours | Yes | The estimation unit for the plan. This is "StoryPoints", "Days" or "Hours". |
| `inferredDates` | enum: None, SprintDates, ReleaseDates | Yes | The inferred dates for the plan. This is "None", "SprintDates" or "ReleaseDates". |
| `startDate` | any | Yes | The start date field for the plan. |

