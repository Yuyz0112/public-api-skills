# GET /time_periods

**Resource:** [Time periods](../resources/Time-periods.md)
**Get time periods**
**Operation ID:** `getTimePeriods`

Returns compact time period records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `start_on` | query | string (date) | No | ISO 8601 date string |
| `end_on` | query | string (date) | No | ISO 8601 date string |
| `workspace` | query | string | Yes | Globally unique identifier for the workspace. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested time periods. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
