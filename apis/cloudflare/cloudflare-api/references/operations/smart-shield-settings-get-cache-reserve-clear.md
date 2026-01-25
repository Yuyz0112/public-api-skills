# GET /zones/{zone_id}/smart_shield/cache_reserve_clear

**Resource:** [Cache Reserve Clear](../resources/Cache-Reserve-Clear.md)
**Get Cache Reserve Clear**
**Operation ID:** `smart-shield-settings-get-cache-reserve-clear`

You can use Cache Reserve Clear to clear your Cache Reserve, but you must first disable Cache Reserve. In most cases, this will be accomplished within 24 hours. You cannot re-enable Cache Reserve while this process is ongoing. Keep in mind that you cannot undo or cancel this operation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | smartshield_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Cache Reserve Clear response. |
| 4XX | Get Cache Reserve Clear failure response. |

## Security

- **api_token**
- **api_email**
- **api_key**
