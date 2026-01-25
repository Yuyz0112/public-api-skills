# GET /accounts/{account_id}/dex/fleet-status/devices

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**List fleet status devices**
**Operation ID:** `dex-fleet-status-devices`

List details for devices using WARP

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | Unique identifier for account |
| `to` | query | digital-experience-monitoring_timestamp | Yes | Time range end in ISO format |
| `from` | query | digital-experience-monitoring_timestamp | Yes | Time range beginning in ISO format |
| `page` | query | digital-experience-monitoring_page | Yes | Page number |
| `per_page` | query | digital-experience-monitoring_per_page | Yes | Number of results per page |
| `sort_by` | query | digital-experience-monitoring_sort_by | No | Dimension to sort results by |
| `colo` | query | digital-experience-monitoring_colo | No | Cloudflare colo |
| `device_id` | query | digital-experience-monitoring_device_id | No | Device-specific ID, given as UUID v4 |
| `mode` | query | digital-experience-monitoring_mode | No | The mode under which the WARP client is run |
| `status` | query | digital-experience-monitoring_status | No | Network status |
| `platform` | query | digital-experience-monitoring_platform | No | Operating system |
| `version` | query | digital-experience-monitoring_version | No | WARP client version |
| `source` | query | digital-experience-monitoring_source | No | Source:
  * `hourly` - device details aggregated hourly, up to 7 days prior
  * `last_seen` - device details, up to 24 hours prior
  * `raw` - device details, up to 7 days prior
 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List devices response |
| 4XX | List devices response failure |

**Success Response Schema:**

[digital-experience-monitoring_fleet_status_devices_response](../schemas/digital-experience-monitoring/digital-experience-monitoring-fleet-status-devices-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
