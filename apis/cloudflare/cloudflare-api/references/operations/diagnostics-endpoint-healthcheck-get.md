# GET /accounts/{account_id}/diagnostics/endpoint-healthchecks/{id}

**Resource:** [Endpoint Health Checks](../resources/Endpoint-Health-Checks.md)
**Get Endpoint Health Check**
**Operation ID:** `diagnostics-endpoint-healthcheck-get`

Get a single Endpoint Health Check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-transit_identifier | Yes |  |
| `id` | path | magic-transit_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Endpoint Health Checks response. |
| 4XX | Endpoint Health Check failure. |

**Success Response Schema:**

[magic-transit_endpoint_health_check_response_single](../schemas/magic-transit/magic-transit-endpoint-health-check-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
