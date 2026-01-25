# PUT /zones/{zone_id}/activation_check

**Resource:** [Zone](../resources/Zone.md)
**Rerun the Activation Check**
**Operation ID:** `put-zones-zone_id-activation_check`

Triggeres a new activation check for a PENDING Zone. This can be
triggered every 5 min for paygo/ent customers, every hour for FREE
Zones.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zone-activation_identifier | Yes | Zone ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |
| 4XX | Client Error |

## Security

- **api_token**
- **api_email**
- **api_key**
