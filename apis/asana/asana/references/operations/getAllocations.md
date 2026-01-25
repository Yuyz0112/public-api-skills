# GET /allocations

**Resource:** [Allocations](../resources/Allocations.md)
**Get multiple allocations**
**Operation ID:** `getAllocations`

Returns a list of allocations filtered to a specific project, user or placeholder.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parent` | query | string | No | Globally unique identifier for the project to filter allocations by. |
| `assignee` | query | string | No | Globally unique identifier for the user or placeholder the allocation is assigned to. |
| `workspace` | query | string | No | Globally unique identifier for the workspace. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested allocations. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
