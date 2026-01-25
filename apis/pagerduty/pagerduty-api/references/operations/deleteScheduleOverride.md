# DELETE /schedules/{id}/overrides/{override_id}

**Resource:** [Schedules](../resources/Schedules.md)
**Delete an override**
**Operation ID:** `deleteScheduleOverride`

Remove an override.

You cannot remove a past override.

If the override start time is before the current time, but the end time is after the current time, the override will be truncated to the current time.

If the override is truncated, the status code will be 200 OK, as opposed to a 204 No Content for a successful delete.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The override was truncated. |
| 204 | The override was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

