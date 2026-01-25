# GET /portfolios

**Resource:** [Portfolios](../resources/Portfolios.md)
**Get multiple portfolios**
**Operation ID:** `getPortfolios`

<b>Required scope: </b><code>portfolios:read</code>

Returns a list of the portfolios in compact representation that are owned by the current API user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workspace` | query | string | Yes | The workspace or organization to filter portfolios on. |
| `owner` | query | string | No | The user who owns the portfolio. Currently, API users can only get a list of portfolios that they themselves own, unless the request is made from a Service Account. In the case of a Service Account, if this parameter is specified, then all portfolios owned by this parameter are returned. Otherwise, all portfolios across the workspace are returned. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved portfolios. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:read
