# POST /portfolios/{portfolio_gid}/addItem

**Resource:** [Portfolios](../resources/Portfolios.md)
**Add a portfolio item**
**Operation ID:** `addItemForPortfolio`

<b>Required scope: </b><code>portfolios:write</code>

Add an item to a portfolio.
Returns an empty data block.

## Request Body

Information about the item being inserted.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the item to the portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:write
