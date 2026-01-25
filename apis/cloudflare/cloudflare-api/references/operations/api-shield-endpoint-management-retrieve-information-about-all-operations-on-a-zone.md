# GET /zones/{zone_id}/api_gateway/operations

**Resource:** [API Shield Endpoint Management](../resources/API-Shield-Endpoint-Management.md)
**Retrieve information about all operations on a zone**
**Operation ID:** `api-shield-endpoint-management-retrieve-information-about-all-operations-on-a-zone`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order` | query | enum: method, host, endpoint... | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve information about all operations on a zone response |
| 4XX | Retrieve information about all operations on a zone response failure |

**Success Response Schema:**

[api-shield_multiple-operation-response-paginated](../schemas/api-shield/api-shield-multiple-operation-response-paginated.md)

## Security

- **api_email**
- **api_key**
- **api_token**
