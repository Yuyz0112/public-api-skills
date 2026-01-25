# GET /accounts/{account_id}/devices/policy/{policy_id}/fallback_domains

**Resource:** [Devices](../resources/Devices.md)
**Get the Local Domain Fallback list for a device settings profile**
**Operation ID:** `devices-get-local-domain-fallback-list-for-a-device-settings-policy`

Fetches the list of domains to bypass Gateway DNS resolution from a specified device settings profile. These domains will use the specified local DNS resolver instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | teams-devices_schemas-uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Local Domain Fallback list for a device settings profile response. |
| 4XX | Get the Local Domain Fallback list for a device settings profile response failure. |

**Success Response Schema:**

[teams-devices_fallback_domain_response_collection](../schemas/teams-devices/teams-devices-fallback-domain-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
