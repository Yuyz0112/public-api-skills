# GET /zones/{zone_id}/devices/policy/certificates

**Resource:** [Devices](../resources/Devices.md)
**Get device certificate provisioning status**
**Operation ID:** `devices-get-policy-certificates`

Fetches device certificate provisioning.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get WARP client provision certificates enabled status response. |
| 4XX | Get WARP client provision certificates enabled status failure. |

**Success Response Schema:**

[teams-devices_devices_policy_certificates_single](../schemas/teams-devices/teams-devices-devices-policy-certificates-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
