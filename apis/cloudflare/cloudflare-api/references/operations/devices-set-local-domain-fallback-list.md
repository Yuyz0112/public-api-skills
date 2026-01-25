# PUT /accounts/{account_id}/devices/policy/fallback_domains

**Resource:** [Devices](../resources/Devices.md)
**Set your Local Domain Fallback list**
**Operation ID:** `devices-set-local-domain-fallback-list`

Sets the list of domains to bypass Gateway DNS resolution. These domains will use the specified local DNS resolver instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [teams-devices_fallback_domain](../schemas/teams-devices/teams-devices-fallback-domain.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set your Local Domain Fallback list response. |
| 4XX | Set your Local Domain Fallback list response failure. |

**Success Response Schema:**

[teams-devices_fallback_domain_response_collection](../schemas/teams-devices/teams-devices-fallback-domain-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
