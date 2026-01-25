# GET /accounts/{account_id}/dex/traceroute-tests/{test_id}/network-path

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**Get network path breakdown for a traceroute test**
**Operation ID:** `dex-endpoints-traceroute-test-network-path`

Get a breakdown of metrics by hop for individual traceroute test runs

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account |
| `test_id` | path | digital-experience-monitoring_uuid | Yes | unique identifier for a specific test |
| `deviceId` | query | string | Yes | Device to filter tracroute result runs to |
| `from` | query | string | Yes | Start time for aggregate metrics in ISO ms |
| `to` | query | string | Yes | End time for aggregate metrics in ISO ms |
| `interval` | query | enum: minute, hour | Yes | Time interval for aggregate time slots. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DEX traceroute test network path response |
| 4XX | DEX traceroute test network path failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
