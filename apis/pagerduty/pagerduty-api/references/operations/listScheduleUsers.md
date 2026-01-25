# GET /schedules/{id}/users

**Resource:** [Schedules](../resources/Schedules.md)
**List users on call.**
**Operation ID:** `listScheduleUsers`

List all of the users on call in a given schedule for a given time range.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `users.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The users on the given schedule. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

