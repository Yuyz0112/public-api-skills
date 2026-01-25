# Devices

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/devices` | List devices (deprecated) | [View](../operations/devices-list-devices.md) |
| GET | `/accounts/{account_id}/devices/policies` | List device settings profiles | [View](../operations/devices-list-device-settings-policies.md) |
| GET | `/accounts/{account_id}/devices/policy` | Get the default device settings profile | [View](../operations/devices-get-default-device-settings-policy.md) |
| POST | `/accounts/{account_id}/devices/policy` | Create a device settings profile | [View](../operations/devices-create-device-settings-policy.md) |
| PATCH | `/accounts/{account_id}/devices/policy` | Update the default device settings profile | [View](../operations/devices-update-default-device-settings-policy.md) |
| GET | `/accounts/{account_id}/devices/policy/exclude` | Get the Split Tunnel exclude list | [View](../operations/devices-get-split-tunnel-exclude-list.md) |
| PUT | `/accounts/{account_id}/devices/policy/exclude` | Set the Split Tunnel exclude list | [View](../operations/devices-set-split-tunnel-exclude-list.md) |
| GET | `/accounts/{account_id}/devices/policy/fallback_domains` | Get your Local Domain Fallback list | [View](../operations/devices-get-local-domain-fallback-list.md) |
| PUT | `/accounts/{account_id}/devices/policy/fallback_domains` | Set your Local Domain Fallback list | [View](../operations/devices-set-local-domain-fallback-list.md) |
| GET | `/accounts/{account_id}/devices/policy/include` | Get the Split Tunnel include list | [View](../operations/devices-get-split-tunnel-include-list.md) |
| PUT | `/accounts/{account_id}/devices/policy/include` | Set the Split Tunnel include list | [View](../operations/devices-set-split-tunnel-include-list.md) |
| GET | `/accounts/{account_id}/devices/policy/{policy_id}` | Get device settings profile by ID | [View](../operations/devices-get-device-settings-policy-by-id.md) |
| DELETE | `/accounts/{account_id}/devices/policy/{policy_id}` | Delete a device settings profile | [View](../operations/devices-delete-device-settings-policy.md) |
| PATCH | `/accounts/{account_id}/devices/policy/{policy_id}` | Update a device settings profile | [View](../operations/devices-update-device-settings-policy.md) |
| GET | `/accounts/{account_id}/devices/policy/{policy_id}/exclude` | Get the Split Tunnel exclude list for a device settings profile | [View](../operations/devices-get-split-tunnel-exclude-list-for-a-device-settings-policy.md) |
| PUT | `/accounts/{account_id}/devices/policy/{policy_id}/exclude` | Set the Split Tunnel exclude list for a device settings profile | [View](../operations/devices-set-split-tunnel-exclude-list-for-a-device-settings-policy.md) |
| GET | `/accounts/{account_id}/devices/policy/{policy_id}/fallback_domains` | Get the Local Domain Fallback list for a device settings profile | [View](../operations/devices-get-local-domain-fallback-list-for-a-device-settings-policy.md) |
| PUT | `/accounts/{account_id}/devices/policy/{policy_id}/fallback_domains` | Set the Local Domain Fallback list for a device settings profile | [View](../operations/devices-set-local-domain-fallback-list-for-a-device-settings-policy.md) |
| GET | `/accounts/{account_id}/devices/policy/{policy_id}/include` | Get the Split Tunnel include list for a device settings profile | [View](../operations/devices-get-split-tunnel-include-list-for-a-device-settings-policy.md) |
| PUT | `/accounts/{account_id}/devices/policy/{policy_id}/include` | Set the Split Tunnel include list for a device settings profile | [View](../operations/devices-set-split-tunnel-include-list-for-a-device-settings-policy.md) |
| POST | `/accounts/{account_id}/devices/revoke` | Revoke devices (deprecated) | [View](../operations/devices-revoke-devices.md) |
| POST | `/accounts/{account_id}/devices/unrevoke` | Unrevoke devices (deprecated) | [View](../operations/devices-unrevoke-devices.md) |
| GET | `/accounts/{account_id}/devices/{device_id}` | Get device (deprecated) | [View](../operations/devices-device-details.md) |
| GET | `/accounts/{account_id}/devices/{device_id}/override_codes` | Get override codes (deprecated)
 | [View](../operations/devices-list-admin-override-code-for-device.md) |
| GET | `/zones/{zone_id}/devices/policy/certificates` | Get device certificate provisioning status | [View](../operations/devices-get-policy-certificates.md) |
| PATCH | `/zones/{zone_id}/devices/policy/certificates` | Update device certificate provisioning status | [View](../operations/devices-update-policy-certificates.md) |
