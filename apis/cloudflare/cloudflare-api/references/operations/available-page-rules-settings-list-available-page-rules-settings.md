# GET /zones/{zone_id}/pagerules/settings

**Resource:** [Available Page Rules settings](../resources/Available-Page-Rules-settings.md)
**List available Page Rules settings**
**Operation ID:** `available-page-rules-settings-list-available-page-rules-settings`
⚠️ **Deprecated**

Returns a list of settings (and their details) that Page Rules can apply to matching requests.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List available Page Rules settings response |
| 4XX | List available Page Rules settings response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
