# GET /zones/{zone_id}/cache/variants

**Resource:** [Zone Cache Settings](../resources/Zone-Cache-Settings.md)
**Get variants setting**
**Operation ID:** `zone-cache-settings-get-variants-setting`

Variant support enables caching variants of images with certain file extensions in addition to the original. This only applies when the origin server sends the 'Vary: Accept' response header. If the origin server sends 'Vary: Accept' but does not serve the variant requested, the response will not be cached. This will be indicated with BYPASS cache status in the response headers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get variants setting response. |
| 4XX | Get variants setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
