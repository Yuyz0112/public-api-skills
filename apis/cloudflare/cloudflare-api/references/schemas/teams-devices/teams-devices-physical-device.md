# teams-devices_physical_device

A WARP Device.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_registrations` | integer | Yes | The number of active registrations for the device. Active registrations are those which haven't been revoked or deleted. |
| `client_version` | string | No | Version of the WARP client. |
| `created_at` | string | Yes | The RFC3339 timestamp when the device was created. |
| `deleted_at` | string | No | The RFC3339 timestamp when the device was deleted. |
| `device_type` | string | No | The device operating system. |
| `hardware_id` | string | No | A string that uniquely identifies the hardware or virtual machine (VM). |
| `id` | string | Yes | The unique ID of the device. |
| `last_seen_at` | string | Yes | The RFC3339 timestamp when the device was last seen. |
| `last_seen_registration` | object | No | The last seen registration for the device. |
| `last_seen_user` | object | No | The last user to use the WARP device. |
| `mac_address` | string | No | The device MAC address. |
| `manufacturer` | string | No | The device manufacturer. |
| `model` | string | No | The model name of the device. |
| `name` | string | Yes | The name of the device. |
| `os_version` | string | No | The device operating system version number. |
| `os_version_extra` | string | No | Additional operating system version details. For Windows, the UBR (Update Build Revision). For Mac or iOS, the Product Version Extra. For Linux, the distribution name and version. |
| `public_ip` | string | No | **Deprecated**: IP information is provided by DEX - see https://developers.cloudflare.com/api/resources/zero_trust/subresources/dex/subresources/fleet_status/subresources/devices/methods/list/
 |
| `serial_number` | string | No | The device serial number. |
| `updated_at` | string | Yes | The RFC3339 timestamp when the device was last updated. |

