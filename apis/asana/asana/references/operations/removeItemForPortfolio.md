# POST /portfolios/{portfolio_gid}/removeItem

**Resource:** [Portfolios](../resources/Portfolios.md)
**Remove a portfolio item**
**Operation ID:** `removeItemForPortfolio`

<b>Required scope: </b><code>portfolios:write</code>

Remove an item from a portfolio.
Returns an empty data block.

## Request Body

Information about the item being removed.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the item from the portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:write
