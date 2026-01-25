# GET /accounts/{account_id}/devices/posture/{rule_id}

**Resource:** [Device posture rules](../resources/Device-posture-rules.md)
**Get device posture rule details**
**Operation ID:** `device-posture-rules-device-posture-rules-details`

Fetches a single device posture rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | teams-devices_uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get device posture rule details response. |
| 4XX | Get device posture rule details response failure. |

**Success Response Schema:**

[teams-devices_single_response](../schemas/teams-devices/teams-devices-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
