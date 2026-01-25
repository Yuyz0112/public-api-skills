# PUT /accounts/{account_id}/access/ai-controls/mcp/portals/{id}

**Resource:** [MCP Portal](../resources/MCP-Portal.md)
**Update a MCP Portal**
**Operation ID:** `mcp-portals-api-update-portals`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated Object |
| 400 | Input Validation Error |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
