# GET /goals

**Resource:** [Goals](../resources/Goals.md)
**Get goals**
**Operation ID:** `getGoals`

<b>Required scope: </b><code>goals:read</code>

Returns compact goal records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `portfolio` | query | string | No | Globally unique identifier for supporting portfolio. |
| `project` | query | string | No | Globally unique identifier for supporting project. |
| `task` | query | string | No | Globally unique identifier for supporting task. |
| `is_workspace_level` | query | boolean | No | Filter to goals with is_workspace_level set to query value. Must be used with the workspace parameter. |
| `team` | query | string | No | Globally unique identifier for the team. |
| `workspace` | query | string | No | Globally unique identifier for the workspace. |
| `time_periods` | query | string[] | No | Globally unique identifiers for the time periods. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested goals. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: goals:read
