# GET /portfolios/{portfolio_gid}/items

**Resource:** [Portfolios](../resources/Portfolios.md)
**Get portfolio items**
**Operation ID:** `getItemsForPortfolio`

<b>Required scope: </b><code>portfolios:read</code>

Get a list of the items in compact form in a portfolio.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested portfolio's items. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:read
