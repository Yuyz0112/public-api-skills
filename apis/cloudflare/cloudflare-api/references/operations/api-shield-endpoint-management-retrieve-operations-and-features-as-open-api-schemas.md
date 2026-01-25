# GET /zones/{zone_id}/api_gateway/schemas

**Resource:** [API Shield Endpoint Management](../resources/API-Shield-Endpoint-Management.md)
**Retrieve operations and features as OpenAPI schemas**
**Operation ID:** `api-shield-endpoint-management-retrieve-operations-and-features-as-open-api-schemas`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `host` | query | string[] | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve operations and features as OpenAPI schemas response |
| 4XX | Retrieve operations and features as OpenAPI schemas response failure |

**Success Response Schema:**

[api-shield_schema-response-with-thresholds](../schemas/api-shield/api-shield-schema-response-with-thresholds.md)

## Security

- **api_email**
- **api_key**
- **api_token**
