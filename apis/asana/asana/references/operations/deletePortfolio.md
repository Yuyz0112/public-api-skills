# DELETE /portfolios/{portfolio_gid}

**Resource:** [Portfolios](../resources/Portfolios.md)
**Delete a portfolio**
**Operation ID:** `deletePortfolio`

An existing portfolio can be deleted by making a DELETE request on
the URL for that portfolio.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
