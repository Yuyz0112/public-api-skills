# GET /schedules/{id}/overrides

**Resource:** [Schedules](../resources/Schedules.md)
**List overrides**
**Operation ID:** `listScheduleOverrides`

List overrides for a given time range.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.read`


## Responses

| Status | Description |
|--------|-------------|
| 201 | The collection of override objects returned by the query. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

