# POST /goals/{goal_gid}/setMetricCurrentValue

**Resource:** [Goals](../resources/Goals.md)
**Update a goal metric**
**Operation ID:** `updateGoalMetric`

Updates a goal's existing metric's `current_number_value` if one exists,
otherwise responds with a 400 status code.

Returns the complete updated goal metric record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The updated fields for the goal metric.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the goal metric. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
