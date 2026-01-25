# DELETE /schedules/{id}

**Resource:** [Schedules](../resources/Schedules.md)
**Delete a schedule**
**Operation ID:** `deleteSchedule`

Delete an on-call schedule.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The schedule was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

