# GET /accounts/{account_id}/dex/colos

**Resource:** [DEX Synthetic Application Monitoring](../resources/DEX-Synthetic-Application-Monitoring.md)
**List Cloudflare colos**
**Operation ID:** `dex-endpoints-list-colos`

List Cloudflare colos that account's devices were connected to during a time period, sorted by usage starting from the most used colo. Colos without traffic are also returned and sorted alphabetically.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path. |
| `from` | query | string | Yes | Start time for connection period in ISO (RFC3339 - ISO 8601) format |
| `to` | query | string | Yes | End time for connection period in ISO (RFC3339 - ISO 8601) format |
| `sortBy` | query | enum: fleet-status-usage, application-tests-usage | No | Type of usage that colos should be sorted by. If unspecified, returns all Cloudflare colos sorted alphabetically. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List colos response |
| 4XX | List colos failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
