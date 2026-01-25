# POST /accounts/{account_id}/devices/posture/integration

**Resource:** [Device Posture Integrations](../resources/Device-Posture-Integrations.md)
**Create a device posture integration**
**Operation ID:** `device-posture-integrations-create-device-posture-integration`

Create a new device posture integration.

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
| 200 | Create a device posture integration response. |
| 4XX | Create a device posture integration response failure. |

**Success Response Schema:**

[teams-devices_schemas-single_response](../schemas/teams-devices/teams-devices-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
