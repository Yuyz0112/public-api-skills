# PUT /accounts/{account_id}/devices/networks/{network_id}

**Resource:** [Device Managed Networks](../resources/Device-Managed-Networks.md)
**Update a device managed network**
**Operation ID:** `device-managed-networks-update-device-managed-network`

Updates a configured device managed network.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `network_id` | path | teams-devices_uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a device managed network response. |
| 4XX | Update a device managed network response failure. |

**Success Response Schema:**

[teams-devices_components-schemas-single_response](../schemas/teams-devices/teams-devices-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
