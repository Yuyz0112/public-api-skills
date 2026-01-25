# POST /portfolios/{portfolio_gid}/removeMembers

**Resource:** [Portfolios](../resources/Portfolios.md)
**Remove users from a portfolio**
**Operation ID:** `removeMembersForPortfolio`

Removes the specified list of users from members of the portfolio.
Returns the updated portfolio record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the members being removed.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the members from the portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
