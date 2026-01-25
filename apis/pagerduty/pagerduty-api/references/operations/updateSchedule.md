# PUT /schedules/{id}

**Resource:** [Schedules](../resources/Schedules.md)
**Update a schedule**
**Operation ID:** `updateSchedule`

Update an existing on-call schedule.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.write`


## Request Body

The schedule to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated schedule. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

