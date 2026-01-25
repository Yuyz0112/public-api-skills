# POST /portfolios/{portfolio_gid}/addMembers

**Resource:** [Portfolios](../resources/Portfolios.md)
**Add users to a portfolio**
**Operation ID:** `addMembersForPortfolio`

Adds the specified list of users as members of the portfolio.
Returns the updated portfolio record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the members being added.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added members to the portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
