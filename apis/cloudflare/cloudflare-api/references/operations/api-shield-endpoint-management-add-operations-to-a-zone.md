# POST /zones/{zone_id}/api_gateway/operations

**Resource:** [API Shield Endpoint Management](../resources/API-Shield-Endpoint-Management.md)
**Add operations to a zone**
**Operation ID:** `api-shield-endpoint-management-add-operations-to-a-zone`

Add one or more operations to a zone. Endpoints can contain path variables. Host, method, endpoint will be normalized to a canoncial form when creating an operation and must be unique on the zone. Inserting an operation that matches an existing one will return the record of the already existing operation and update its last_updated date.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [api-shield_basic_operation](../schemas/api-shield/api-shield-basic-operation.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add operations to a zone response |
| 4XX | Add operations to a zone response failure |

**Success Response Schema:**

[api-shield_multiple-operation-response](../schemas/api-shield/api-shield-multiple-operation-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
