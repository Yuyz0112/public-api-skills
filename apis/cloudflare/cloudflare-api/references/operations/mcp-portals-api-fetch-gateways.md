# GET /accounts/{account_id}/access/ai-controls/mcp/portals/{id}

**Resource:** [MCP Portal](../resources/MCP-Portal.md)
**Read details of an MCP Portal**
**Operation ID:** `mcp-portals-api-fetch-gateways`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a single object if found |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
