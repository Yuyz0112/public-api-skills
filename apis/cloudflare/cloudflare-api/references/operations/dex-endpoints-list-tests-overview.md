# GET /accounts/{account_id}/dex/tests/overview

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**List DEX test analytics**
**Operation ID:** `dex-endpoints-list-tests-overview`

List DEX tests with overview metrics

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path. |
| `colo` | query | string | No | Optionally filter result stats to a Cloudflare colo. Cannot be used in combination with deviceId param. |
| `testName` | query | string | No | Optionally filter results by test name |
| `deviceId` | query | string[] | No | Optionally filter result stats to a specific device(s). Cannot be used in combination with colo param. |
| `page` | query | number | No | Page number of paginated results |
| `per_page` | query | number | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | success response |
| 4XX | failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
