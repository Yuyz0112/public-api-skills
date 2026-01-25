# PUT /admin/api/2020-10/themes/{theme_id}/assets.json

**Resource:** [online-store/asset](../resources/online-store-asset.md)
**Creates or updates an asset for a theme.
          In the PUT request, you can include the src or source_key property to create the asset from an existing file.**
**Operation ID:** `update_themes_param_theme_id_assets`

https://shopify.dev/docs/admin-api/rest/reference/online-store/asset#update-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `theme_id` | path | string | Yes | theme_id |
| `src` | query | any | No | The source URL of an image. Include in the body of the PUT request to upload the image to Shopify. |
| `source_key` | query | any | No | The path within the theme to an existing asset. Include in the body of the PUT request to create a duplicate asset. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

