# PATCH /accounts/{account_id}/devices/posture/integration/{integration_id}

**Resource:** [Device Posture Integrations](../resources/Device-Posture-Integrations.md)
**Update a device posture integration**
**Operation ID:** `device-posture-integrations-update-device-posture-integration`

Updates a configured device posture integration.

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
| 200 | Update a device posture integration response. |
| 4XX | Update a device posture integration response failure. |

**Success Response Schema:**

[teams-devices_schemas-single_response](../schemas/teams-devices/teams-devices-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
