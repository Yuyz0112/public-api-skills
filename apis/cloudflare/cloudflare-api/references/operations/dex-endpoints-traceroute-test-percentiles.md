# GET /accounts/{account_id}/dex/traceroute-tests/{test_id}/percentiles

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**Get percentiles for a traceroute test**
**Operation ID:** `dex-endpoints-traceroute-test-percentiles`

Get percentiles for a traceroute test for a given time period between 1 hour and 7 days.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path. |
| `test_id` | path | digital-experience-monitoring_uuid | Yes | unique identifier for a specific test |
| `deviceId` | query | string[] | No | Optionally filter result stats to a specific device(s). Cannot be used in combination with colo param. |
| `from` | query | string | Yes | Start time for the query in ISO (RFC3339 - ISO 8601) format |
| `to` | query | string | Yes | End time for the query in ISO (RFC3339 - ISO 8601) format |
| `colo` | query | string | No | Optionally filter result stats to a Cloudflare colo. Cannot be used in combination with deviceId param. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DEX Traceroute test percentiles response |
| 4XX | DEX Traceroute test percentiles failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
