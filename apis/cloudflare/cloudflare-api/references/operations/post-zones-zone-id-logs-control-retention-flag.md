# POST /zones/{zone_id}/logs/control/retention/flag

**Resource:** [Logs Received](../resources/Logs-Received.md)
**Update log retention flag**
**Operation ID:** `post-zones-zone_id-logs-control-retention-flag`

Updates log retention flag for Logpull API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logcontrol_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [logcontrol_retention_flag](../schemas/logcontrol/logcontrol-retention-flag.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update log retention flag response |
| 4XX | Update log retention flag response failure |

**Success Response Schema:**

[logcontrol_retention_flag_response_single](../schemas/logcontrol/logcontrol-retention-flag-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
