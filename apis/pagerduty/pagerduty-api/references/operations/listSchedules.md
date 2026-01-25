# GET /schedules

**Resource:** [Schedules](../resources/Schedules.md)
**List schedules**
**Operation ID:** `listSchedules`

List the on-call schedules.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of schedule objects. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

