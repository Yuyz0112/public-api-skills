# POST /schedules/preview

**Resource:** [Schedules](../resources/Schedules.md)
**Preview a schedule**
**Operation ID:** `createSchedulePreview`

Preview what an on-call schedule would look like without saving it.

A Schedule determines the time periods that users are On-Call.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.write`


## Request Body

The schedule to be previewed.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | What the schedule will look like if posted. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

