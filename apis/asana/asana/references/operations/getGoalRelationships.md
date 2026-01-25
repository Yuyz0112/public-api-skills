# GET /goal_relationships

**Resource:** [Goal relationships](../resources/Goal-relationships.md)
**Get goal relationships**
**Operation ID:** `getGoalRelationships`

Returns compact goal relationship records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `supported_goal` | query | string | Yes | Globally unique identifier for the supported goal in the goal relationship. |
| `resource_subtype` | query | string | No | If provided, filter to goal relationships with a given resource_subtype. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested goal relationships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
