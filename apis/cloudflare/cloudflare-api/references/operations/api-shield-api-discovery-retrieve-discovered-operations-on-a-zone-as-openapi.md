# GET /zones/{zone_id}/api_gateway/discovery

**Resource:** [API Shield API Discovery](../resources/API-Shield-API-Discovery.md)
**Retrieve discovered operations on a zone rendered as OpenAPI schemas**
**Operation ID:** `api-shield-api-discovery-retrieve-discovered-operations-on-a-zone-as-openapi`

Retrieve the most up to date view of discovered operations, rendered as OpenAPI schemas

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve discovered operations on a zone, rendered as OpenAPI schemas response |
| 4XX | Retrieve discovered operations on a zone, rendered as OpenAPI schemas response failure |

**Success Response Schema:**

[api-shield_schema_response_discovery](../schemas/api-shield/api-shield-schema-response-discovery.md)

## Security

- **api_email**
- **api_key**
- **api_token**
