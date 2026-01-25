# GET /accounts/{account_id}/devices/posture/integration/{integration_id}

**Resource:** [Device Posture Integrations](../resources/Device-Posture-Integrations.md)
**Get device posture integration details**
**Operation ID:** `device-posture-integrations-device-posture-integration-details`

Fetches details for a single device posture integration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `integration_id` | path | teams-devices_uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get device posture integration details response. |
| 4XX | Get device posture integration details response failure. |

**Success Response Schema:**

[teams-devices_schemas-single_response](../schemas/teams-devices/teams-devices-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
