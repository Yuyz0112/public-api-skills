# GET /accounts/{account_id}/dex/devices/{device_id}/fleet-status/live

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**Get the live status of a latest device**
**Operation ID:** `devices-live-status`

Get the live status of a latest device given device_id from the device_state table

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | Unique identifier for account |
| `device_id` | path | digital-experience-monitoring_device_id | Yes | Unique identifier for device |
| `since_minutes` | query | digital-experience-monitoring_since_minutes | Yes | Number of minutes before current time |
| `time_now` | query | digital-experience-monitoring_time_now | No | Number of minutes before current time |
| `colo` | query | digital-experience-monitoring_colo | No | List of data centers to filter results |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the live status of a latest device |
| 4XX | Get the live status of a latest device failure |

**Success Response Schema:**

[digital-experience-monitoring_device](../schemas/digital-experience-monitoring/digital-experience-monitoring-device.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
