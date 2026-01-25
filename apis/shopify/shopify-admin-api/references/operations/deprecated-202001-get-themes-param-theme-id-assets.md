# GET /admin/api/2020-01/themes/{theme_id}/assets.json

**Resource:** [online-store/asset](../resources/online-store-asset.md)
**Retrieves a single asset for a theme by its key.
          To retrieve a single asset, include asset[key]=#{asset_key} as a request parameter. For example, to retrieve the asset with a key of templates/index.liquid, the request might be /admin/themes/828155753/assets.json?asset[key]=templates/index.liquid.
          For more information on the key property, see Asset properties.**
**Operation ID:** `deprecated_202001_get_themes_param_theme_id_assets`

https://shopify.dev/docs/admin-api/rest/reference/online-store/asset#show-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `theme_id` | path | string | Yes | theme_id |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names |
| `asset[key]` | query | string | No | asset[key] |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

