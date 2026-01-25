# DELETE /accounts/{account_id}/access/ai-controls/mcp/portals/{id}

**Resource:** [MCP Portal](../resources/MCP-Portal.md)
**Delete a MCP Portal**
**Operation ID:** `mcp-portals-api-delete-portals`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the Object if it was successfully deleted |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
