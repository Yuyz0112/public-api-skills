# digital-experience-monitoring_warp_config_change_event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `device_id` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | No |  |
| `device_registration` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | No |  |
| `from` | [digital-experience-monitoring_warp_config_details](digital-experience-monitoring-warp-config-details.md) | No |  |
| `hostname` | string | No | The hostname of the machine the event is from |
| `serial_number` | string | No | The serial number of the machine the event is from |
| `timestamp` | [digital-experience-monitoring_timestamp](digital-experience-monitoring-timestamp.md) | No |  |
| `to` | [digital-experience-monitoring_warp_config_details](digital-experience-monitoring-warp-config-details.md) | No |  |
| `user_email` | string | No | Email tied to the device |

