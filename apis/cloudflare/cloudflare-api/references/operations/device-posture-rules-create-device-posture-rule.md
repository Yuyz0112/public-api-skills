# POST /accounts/{account_id}/devices/posture

**Resource:** [Device posture rules](../resources/Device-posture-rules.md)
**Create a device posture rule**
**Operation ID:** `device-posture-rules-create-device-posture-rule`

Creates a new device posture rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create device posture rule response. |
| 4XX | Create device posture rule response failure. |

**Success Response Schema:**

[teams-devices_single_response](../schemas/teams-devices/teams-devices-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
