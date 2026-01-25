# POST /accounts/{account_id}/diagnostics/endpoint-healthchecks

**Resource:** [Endpoint Health Checks](../resources/Endpoint-Health-Checks.md)
**Endpoint Health Check**
**Operation ID:** `diagnostics-endpoint-healthcheck-create`

Create Endpoint Health Check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-transit_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic-transit_endpoint_health_check](../schemas/magic-transit/magic-transit-endpoint-health-check.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Endpoint Health Check response. |
| 4XX | Endpoint Health Check response failure. |

**Success Response Schema:**

[magic-transit_endpoint_health_check_response_single](../schemas/magic-transit/magic-transit-endpoint-health-check-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
