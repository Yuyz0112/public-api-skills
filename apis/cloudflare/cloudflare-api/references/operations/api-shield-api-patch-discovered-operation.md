# PATCH /zones/{zone_id}/api_gateway/discovery/operations/{operation_id}

**Resource:** [API Shield API Discovery](../resources/API-Shield-API-Discovery.md)
**Patch discovered operation**
**Operation ID:** `api-shield-api-patch-discovered-operation`

Update the `state` on a discovered operation

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch discovered operation response |
| 4XX | Patch discovered operation response failure |

**Success Response Schema:**

[api-shield_patch_discovery_response](../schemas/api-shield/api-shield-patch-discovery-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
