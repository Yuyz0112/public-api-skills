# GET /accounts/{account_id}/dex/fleet-status/over-time

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**List fleet status aggregate details by dimension**
**Operation ID:** `dex-fleet-status-over-time`

List details for devices using WARP, up to 7 days

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | Unique identifier for account |
| `to` | query | digital-experience-monitoring_timestamp | Yes | Time range end in ISO format |
| `from` | query | digital-experience-monitoring_timestamp | Yes | Time range beginning in ISO format |
| `colo` | query | digital-experience-monitoring_colo | No | Cloudflare colo |
| `device_id` | query | digital-experience-monitoring_device_id | No | Device-specific ID, given as UUID v4 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List DEX devices response |
| 4XX | DEX HTTP test details failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
