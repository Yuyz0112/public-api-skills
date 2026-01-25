# DELETE /accounts/{account_id}/devices/posture/{rule_id}

**Resource:** [Device posture rules](../resources/Device-posture-rules.md)
**Delete a device posture rule**
**Operation ID:** `device-posture-rules-delete-device-posture-rule`

Deletes a device posture rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | teams-devices_uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a device posture rule response. |
| 4XX | Delete a device posture rule response failure. |

**Success Response Schema:**

[teams-devices_id_response](../schemas/teams-devices/teams-devices-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
