# PUT /accounts/{account_id}/devices/policy/{policy_id}/fallback_domains

**Resource:** [Devices](../resources/Devices.md)
**Set the Local Domain Fallback list for a device settings profile**
**Operation ID:** `devices-set-local-domain-fallback-list-for-a-device-settings-policy`

Sets the list of domains to bypass Gateway DNS resolution. These domains will use the specified local DNS resolver instead. This will only apply to the specified device settings profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | teams-devices_schemas-uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [teams-devices_fallback_domain](../schemas/teams-devices/teams-devices-fallback-domain.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set the Local Domain Fallback list for a device settings profile response. |
| 4XX | Set the Local Domain Fallback list for a device settings profile response failure. |

**Success Response Schema:**

[teams-devices_fallback_domain_response_collection](../schemas/teams-devices/teams-devices-fallback-domain-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
