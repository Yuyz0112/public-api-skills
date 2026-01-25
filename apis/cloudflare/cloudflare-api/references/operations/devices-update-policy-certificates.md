# PATCH /zones/{zone_id}/devices/policy/certificates

**Resource:** [Devices](../resources/Devices.md)
**Update device certificate provisioning status**
**Operation ID:** `devices-update-policy-certificates`

Enable Zero Trust Clients to provision a certificate, containing a x509 subject, and referenced by Access device posture policies when the client visits MTLS protected domains. This facilitates device posture without a WARP session.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [teams-devices_devices_policy_certificates](../schemas/teams-devices/teams-devices-devices-policy-certificates.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a zone to toggle permission for devices to provision certificates response. |
| 4XX | Patch a zone to toggle permission for devices to provision certificates failure. |

**Success Response Schema:**

[teams-devices_devices_policy_certificates_single](../schemas/teams-devices/teams-devices-devices-policy-certificates-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
