# GET /portfolio_memberships

**Resource:** [Portfolio memberships](../resources/Portfolio-memberships.md)
**Get multiple portfolio memberships**
**Operation ID:** `getPortfolioMemberships`

Returns a list of portfolio memberships in compact representation. You must specify `portfolio`, `portfolio` and `user`, or `workspace` and `user`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved portfolio memberships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
