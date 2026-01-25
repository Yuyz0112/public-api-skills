# POST /schedules

**Resource:** [Schedules](../resources/Schedules.md)
**Create a schedule**
**Operation ID:** `createSchedule`

Create a new on-call schedule.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.write`


## Request Body

The schedule to be created.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The schedule object created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

