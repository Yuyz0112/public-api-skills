# PATCH /zones/{zone_id}/api_gateway/discovery/operations

**Resource:** [API Shield API Discovery](../resources/API-Shield-API-Discovery.md)
**Patch discovered operations**
**Operation ID:** `api-shield-api-patch-discovered-operations`

Update the `state` on one or more discovered operations

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [api-shield_api_discovery_patch_multiple_request](../schemas/api-shield/api-shield-api-discovery-patch-multiple-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch discovered operations response |
| 4XX | Patch discovered operations response failure |

**Success Response Schema:**

[api-shield_patch_discoveries_response](../schemas/api-shield/api-shield-patch-discoveries-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
