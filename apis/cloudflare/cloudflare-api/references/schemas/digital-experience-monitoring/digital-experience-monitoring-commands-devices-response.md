# digital-experience-monitoring_commands_devices_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `devices` | object[] | No | List of eligible devices |

## Nested Fields

### `devices`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deviceId` | string | No | Device identifier (UUID v4) |
| `deviceName` | string | No | Device identifier (human readable) |
| `eligible` | boolean | No | Whether the device is eligible for remote captures |
| `ineligibleReason` | string | No | If the device is not eligible, the reason why. |
| `personEmail` | string | No | User contact email address |
| `platform` | [digital-experience-monitoring_platform](digital-experience-monitoring-platform.md) | No |  |
| `status` | [digital-experience-monitoring_status](digital-experience-monitoring-status.md) | No |  |
| `timestamp` | [digital-experience-monitoring_timestamp](digital-experience-monitoring-timestamp.md) | No |  |
| `version` | [digital-experience-monitoring_version](digital-experience-monitoring-version.md) | No |  |

