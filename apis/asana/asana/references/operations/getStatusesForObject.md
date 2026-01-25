# GET /status_updates

**Resource:** [Status updates](../resources/Status-updates.md)
**Get status updates from an object**
**Operation ID:** `getStatusesForObject`

Returns the compact status update records for all updates on the object.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parent` | query | string | Yes | Globally unique identifier for object to fetch statuses from. Must be a GID for a project, portfolio, or goal. |
| `created_since` | query | string (date-time) | No | Only return statuses that have been created since the given time. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified object's status updates. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
