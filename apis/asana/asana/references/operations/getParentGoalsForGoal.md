# GET /goals/{goal_gid}/parentGoals

**Resource:** [Goals](../resources/Goals.md)
**Get parent goals from a goal**
**Operation ID:** `getParentGoalsForGoal`

<b>Required scope: </b><code>goals:read</code>

Returns a compact representation of all of the parent goals of a goal.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified goal's parent goals. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: goals:read
