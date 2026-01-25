# GET /accounts/{account_id}/dex/traceroute-test-results/{test_result_id}/network-path

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**Get details for a specific traceroute test run**
**Operation ID:** `dex-endpoints-traceroute-test-result-network-path`

Get a breakdown of hops and performance metrics for a specific traceroute test run

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account |
| `test_result_id` | path | digital-experience-monitoring_uuid | Yes | unique identifier for a specific traceroute test |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DEX traceroute test result network path response |
| 4XX | DEX traceroute test result network path failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
