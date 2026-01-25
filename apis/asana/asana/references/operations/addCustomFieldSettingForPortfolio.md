# POST /portfolios/{portfolio_gid}/addCustomFieldSetting

**Resource:** [Portfolios](../resources/Portfolios.md)
**Add a custom field to a portfolio**
**Operation ID:** `addCustomFieldSettingForPortfolio`

<b>Required scope: </b><code>portfolios:write</code>

Custom fields are associated with portfolios by way of custom field settings.  This method creates a setting for the portfolio.

## Request Body

Information about the custom field setting.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the custom field to the portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:write
