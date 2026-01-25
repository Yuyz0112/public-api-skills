# GET /accounts/{account_id}/devices/networks

**Resource:** [Device Managed Networks](../resources/Device-Managed-Networks.md)
**List your device managed networks**
**Operation ID:** `device-managed-networks-list-device-managed-networks`

Fetches a list of managed networks for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List your device managed networks response. |
| 4XX | List your device managed networks response failure. |

**Success Response Schema:**

[teams-devices_components-schemas-response_collection](../schemas/teams-devices/teams-devices-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
