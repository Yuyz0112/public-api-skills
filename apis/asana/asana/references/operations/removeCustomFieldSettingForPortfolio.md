# POST /portfolios/{portfolio_gid}/removeCustomFieldSetting

**Resource:** [Portfolios](../resources/Portfolios.md)
**Remove a custom field from a portfolio**
**Operation ID:** `removeCustomFieldSettingForPortfolio`

<b>Required scope: </b><code>portfolios:write</code>

Removes a custom field setting from a portfolio.

## Request Body

Information about the custom field setting being removed.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the custom field from the portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:write
