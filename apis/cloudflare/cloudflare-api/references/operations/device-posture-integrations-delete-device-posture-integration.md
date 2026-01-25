# DELETE /accounts/{account_id}/devices/posture/integration/{integration_id}

**Resource:** [Device Posture Integrations](../resources/Device-Posture-Integrations.md)
**Delete a device posture integration**
**Operation ID:** `device-posture-integrations-delete-device-posture-integration`

Delete a configured device posture integration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `integration_id` | path | teams-devices_uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a device posture integration response. |
| 4XX | Delete a device posture integration response failure. |

**Success Response Schema:**

[teams-devices_schemas-id_response](../schemas/teams-devices/teams-devices-schemas-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
