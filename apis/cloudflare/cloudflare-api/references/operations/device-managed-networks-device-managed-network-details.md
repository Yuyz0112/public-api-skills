# GET /accounts/{account_id}/devices/networks/{network_id}

**Resource:** [Device Managed Networks](../resources/Device-Managed-Networks.md)
**Get device managed network details**
**Operation ID:** `device-managed-networks-device-managed-network-details`

Fetches details for a single managed network.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `network_id` | path | teams-devices_uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get device managed network details response. |
| 4XX | Get device managed network details response failure. |

**Success Response Schema:**

[teams-devices_components-schemas-single_response](../schemas/teams-devices/teams-devices-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
