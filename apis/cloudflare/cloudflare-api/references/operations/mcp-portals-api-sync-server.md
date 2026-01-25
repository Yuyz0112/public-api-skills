# POST /accounts/{account_id}/access/ai-controls/mcp/servers/{id}/sync

**Resource:** [MCP Portal Servers](../resources/MCP-Portal-Servers.md)
**Sync MCP Server Capabilities**
**Operation ID:** `mcp-portals-api-sync-server`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
