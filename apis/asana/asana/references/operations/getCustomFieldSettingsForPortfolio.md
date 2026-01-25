# GET /portfolios/{portfolio_gid}/custom_field_settings

**Resource:** [Custom field settings](../resources/Custom-field-settings.md)
**Get a portfolio's custom fields**
**Operation ID:** `getCustomFieldSettingsForPortfolio`

Returns a list of all of the custom fields settings on a portfolio, in compact form.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved custom field settings objects for a portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
