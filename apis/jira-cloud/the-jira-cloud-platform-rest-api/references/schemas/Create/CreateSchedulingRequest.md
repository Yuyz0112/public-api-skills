# CreateSchedulingRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dependencies` | enum: Sequential, Concurrent | No | The dependencies for the plan. This must be "Sequential" or "Concurrent". |
| `endDate` | any | No | The end date field for the plan. |
| `estimation` | enum: StoryPoints, Days, Hours | Yes | The estimation unit for the plan. This must be "StoryPoints", "Days" or "Hours". |
| `inferredDates` | enum: None, SprintDates, ReleaseDates | No | The inferred dates for the plan. This must be "None", "SprintDates" or "ReleaseDates". |
| `startDate` | any | No | The start date field for the plan. |

