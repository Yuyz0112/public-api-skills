# GET /accounts/{account_id}/dex/fleet-status/live

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**List fleet status details by dimension**
**Operation ID:** `dex-fleet-status-live`

List details for live (up to 60 minutes) devices using WARP

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | Unique identifier for account |
| `since_minutes` | query | digital-experience-monitoring_since_minutes | Yes | Number of minutes before current time |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List device details (live) response |
| 4XX | List device details (live) response failure |

**Success Response Schema:**

[digital-experience-monitoring_fleet_status_live_response](../schemas/digital-experience-monitoring/digital-experience-monitoring-fleet-status-live-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
