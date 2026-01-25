# DELETE /zones/{zone_id}/api_gateway/operations

**Resource:** [API Shield Endpoint Management](../resources/API-Shield-Endpoint-Management.md)
**Delete multiple operations**
**Operation ID:** `api-shield-endpoint-management-delete-multiple-operations`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [api-shield_object-with-operation-id](../schemas/api-shield/api-shield-object-with-operation-id.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete multiple operations response |
| 4XX | Delete multiple operations response failure |

**Success Response Schema:**

[api-shield_api-response-common](../schemas/api-shield/api-shield-api-response-common.md)

## Security

- **api_email**
- **api_key**
- **api_token**
