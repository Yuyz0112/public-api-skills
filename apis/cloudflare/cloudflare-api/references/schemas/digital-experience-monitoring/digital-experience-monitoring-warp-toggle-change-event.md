# digital-experience-monitoring_warp_toggle_change_event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_name` | string | No | The account name. |
| `account_tag` | string | No | The public account identifier. |
| `device_id` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | No |  |
| `device_registration` | [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | No |  |
| `hostname` | string | No | The hostname of the machine the event is from |
| `serial_number` | string | No | The serial number of the machine the event is from |
| `timestamp` | [digital-experience-monitoring_timestamp](digital-experience-monitoring-timestamp.md) | No |  |
| `toggle` | enum: on, off | No | The state of the WARP toggle. |
| `user_email` | string | No | Email tied to the device |

