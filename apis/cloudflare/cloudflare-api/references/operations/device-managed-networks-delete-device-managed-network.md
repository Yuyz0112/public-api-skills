# DELETE /accounts/{account_id}/devices/networks/{network_id}

**Resource:** [Device Managed Networks](../resources/Device-Managed-Networks.md)
**Delete a device managed network**
**Operation ID:** `device-managed-networks-delete-device-managed-network`

Deletes a device managed network and fetches a list of the remaining device managed networks for an account.

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
| 200 | Delete a device managed network response. |
| 4XX | Delete a device managed network response failure. |

**Success Response Schema:**

[teams-devices_components-schemas-response_collection](../schemas/teams-devices/teams-devices-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
