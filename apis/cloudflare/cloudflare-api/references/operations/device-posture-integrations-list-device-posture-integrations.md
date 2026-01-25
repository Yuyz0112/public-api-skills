# GET /accounts/{account_id}/devices/posture/integration

**Resource:** [Device Posture Integrations](../resources/Device-Posture-Integrations.md)
**List your device posture integrations**
**Operation ID:** `device-posture-integrations-list-device-posture-integrations`

Fetches the list of device posture integrations for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List your device posture integrations response. |
| 4XX | List your device posture integrations response failure. |

**Success Response Schema:**

[teams-devices_schemas-response_collection](../schemas/teams-devices/teams-devices-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
