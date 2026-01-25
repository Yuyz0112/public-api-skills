# DELETE /zones/{zone_id}/hold

**Resource:** [Zone Holds](../resources/Zone-Holds.md)
**Remove Zone Hold**
**Operation ID:** `zones-0-hold-delete`

Stop enforcement of a zone hold on the zone, permanently or temporarily, allowing the
creation and activation of zones with this zone's hostname.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes | Zone ID |
| `hold_after` | query | string | No | If `hold_after` is provided, the hold will be temporarily disabled,
then automatically re-enabled by the system at the time specified
in this RFC3339-formatted timestamp. Otherwise, the hold will be
disabled indefinitely. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |
| 4XX | Client Error |

## Security

- **api_token**
- **api_email**
- **api_key**
