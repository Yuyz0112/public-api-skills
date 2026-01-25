# GET /accounts/{account_id}/dex/traceroute-tests/{test_id}

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**Get details and aggregate metrics for a traceroute test**
**Operation ID:** `dex-endpoints-traceroute-test-details`

Get test details and aggregate performance metrics for an traceroute test for a given time period between 1 hour and 7 days.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | Unique identifier linked to an account |
| `test_id` | path | digital-experience-monitoring_uuid | Yes | Unique identifier for a specific test |
| `deviceId` | query | string[] | No | Optionally filter result stats to a specific device(s). Cannot be used in combination with colo param. |
| `from` | query | string | Yes | Start time for aggregate metrics in ISO ms |
| `to` | query | string | Yes | End time for aggregate metrics in ISO ms |
| `interval` | query | enum: minute, hour | Yes | Time interval for aggregate time slots. |
| `colo` | query | string | No | Optionally filter result stats to a Cloudflare colo. Cannot be used in combination with deviceId param. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DEX traceroute test details response |
| 4XX | DEX traceroute test details response failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
