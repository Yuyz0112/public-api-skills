# POST /accounts/{account_id}/devices/networks

**Resource:** [Device Managed Networks](../resources/Device-Managed-Networks.md)
**Create a device managed network**
**Operation ID:** `device-managed-networks-create-device-managed-network`

Creates a new device managed network.

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
| 200 | Create a device managed networks response. |
| 4XX | Create a device managed networks response failure. |

**Success Response Schema:**

[teams-devices_components-schemas-single_response](../schemas/teams-devices/teams-devices-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
