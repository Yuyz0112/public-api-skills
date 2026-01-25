# GET /accounts/{account_id}/diagnostics/endpoint-healthchecks

**Resource:** [Endpoint Health Checks](../resources/Endpoint-Health-Checks.md)
**List Endpoint Health Checks**
**Operation ID:** `diagnostics-endpoint-healthcheck-list`

List Endpoint Health Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-transit_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Endpoint Health Checks for account. |
| 4XX | Endpoint Health Check response failure. |

**Success Response Schema:**

[magic-transit_endpoint_health_check_response_single](../schemas/magic-transit/magic-transit-endpoint-health-check-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
