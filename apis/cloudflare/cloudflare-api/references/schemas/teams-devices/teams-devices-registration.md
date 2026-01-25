# teams-devices_registration

A WARP configuration tied to a single user. Multiple registrations can be created from a single WARP device.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | Yes | The RFC3339 timestamp when the registration was created. |
| `deleted_at` | string | No | The RFC3339 timestamp when the registration was deleted. |
| `device` | [teams-devices_registration_device_details](teams-devices-registration-device-details.md) | Yes |  |
| `id` | string | Yes | The ID of the registration. |
| `key` | string | Yes | The public key used to connect to the Cloudflare network. |
| `key_type` | string | No | The type of encryption key used by the WARP client for the active key. Currently 'curve25519' for WireGuard and 'secp256r1' for MASQUE. |
| `last_seen_at` | string | Yes | The RFC3339 timestamp when the registration was last seen. |
| `policy` | [teams-devices_policy_summary](teams-devices-policy-summary.md) | No |  |
| `revoked_at` | string | No | The RFC3339 timestamp when the registration was revoked. |
| `tunnel_type` | string | No | Type of the tunnel - wireguard or masque. |
| `updated_at` | string | Yes | The RFC3339 timestamp when the registration was last updated. |
| `user` | [teams-devices_user](teams-devices-user.md) | No |  |

