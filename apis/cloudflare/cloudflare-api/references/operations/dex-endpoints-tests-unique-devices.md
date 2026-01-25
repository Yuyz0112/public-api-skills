# GET /accounts/{account_id}/dex/tests/unique-devices

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**Get count of devices targeted**
**Operation ID:** `dex-endpoints-tests-unique-devices`

Returns unique count of devices that have run synthetic application monitoring tests in the past 7 days.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path. |
| `testName` | query | string | No | Optionally filter results by test name |
| `deviceId` | query | string[] | No | Optionally filter result stats to a specific device(s). Cannot be used in combination with colo param. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DEX unique devices targeted response |
| 4XX | DEX unique devices targeted failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
