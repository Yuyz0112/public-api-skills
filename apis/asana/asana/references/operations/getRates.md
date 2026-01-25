# GET /rates

**Resource:** [Rates](../resources/Rates.md)
**Get multiple rates**
**Operation ID:** `getRates`

Returns a list of `rate` records. The possible types for `parent` in this request are `project`. An additional `resource` (`user` GID or `placeholder` GID) can be passed in to filter to a specific rate.

Modifying placeholder rates is only available for Enterprise and Enterprise+ users.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parent` | query | string | No | Globally unique identifier for `project`. |
| `resource` | query | string | No | Globally unique identifier for `user` or `placeholder`. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested rates. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
