# POST /schedules/{id}/overrides

**Resource:** [Schedules](../resources/Schedules.md)
**Create one or more overrides**
**Operation ID:** `createScheduleOverride`

Create one or more overrides, each for a specific user covering a specified time range. If you create an override on top of an existing override, the last created override will have priority.

A Schedule determines the time periods that users are On-Call.

Note: An older implementation of this endpoint only supported creating a single ocverride per request. That functionality is still supported, but deprecated and may be removed in the future.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#schedules)

Scoped OAuth requires: `schedules.write`


## Request Body

The overrides to be created

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | A list of overrides requested and a status code indicating whether they were created or rejected |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

