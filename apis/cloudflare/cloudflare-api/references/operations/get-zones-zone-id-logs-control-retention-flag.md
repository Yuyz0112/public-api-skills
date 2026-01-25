# GET /zones/{zone_id}/logs/control/retention/flag

**Resource:** [Logs Received](../resources/Logs-Received.md)
**Get log retention flag**
**Operation ID:** `get-zones-zone_id-logs-control-retention-flag`

Gets log retention flag for Logpull API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logcontrol_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get log retention flag response |
| 4XX | Get log retention flag response failure |

**Success Response Schema:**

[logcontrol_retention_flag_response_single](../schemas/logcontrol/logcontrol-retention-flag-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
