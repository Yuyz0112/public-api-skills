# POST /zones/{zone_id}/cache/cache_reserve_clear

**Resource:** [Zone Cache Settings](../resources/Zone-Cache-Settings.md)
**Start Cache Reserve Clear**
**Operation ID:** `zone-cache-settings-start-cache-reserve-clear`

You can use Cache Reserve Clear to clear your Cache Reserve, but you must first disable Cache Reserve. In most cases, this will be accomplished within 24 hours. You cannot re-enable Cache Reserve while this process is ongoing. Keep in mind that you cannot undo or cancel this operation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Request Body

The request body is currently not used.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Start Cache Reserve Clear response. |
| 4XX | Start Cache Reserve Clear failure response. |

## Security

- **api_token**
- **api_email**
- **api_key**
