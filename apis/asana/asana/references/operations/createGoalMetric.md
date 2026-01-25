# POST /goals/{goal_gid}/setMetric

**Resource:** [Goals](../resources/Goals.md)
**Create a goal metric**
**Operation ID:** `createGoalMetric`

Creates and adds a goal metric to a specified goal. Note that this replaces an existing goal metric if one already exists.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The goal metric to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully created a new goal metric. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
