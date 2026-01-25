# PUT /accounts/{account_id}/devices/posture/{rule_id}

**Resource:** [Device posture rules](../resources/Device-posture-rules.md)
**Update a device posture rule**
**Operation ID:** `device-posture-rules-update-device-posture-rule`

Updates a device posture rule.

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
| 200 | Update a device posture rule response. |
| 4XX | Update a device posture rule response failure. |

**Success Response Schema:**

[teams-devices_single_response](../schemas/teams-devices/teams-devices-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
