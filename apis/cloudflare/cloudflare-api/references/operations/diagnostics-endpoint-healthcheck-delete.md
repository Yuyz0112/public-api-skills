# DELETE /accounts/{account_id}/diagnostics/endpoint-healthchecks/{id}

**Resource:** [Endpoint Health Checks](../resources/Endpoint-Health-Checks.md)
**Delete Endpoint Health Check**
**Operation ID:** `diagnostics-endpoint-healthcheck-delete`

Delete Endpoint Health Check.

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

[magic-transit_api-response-common](../schemas/magic-transit/magic-transit-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
