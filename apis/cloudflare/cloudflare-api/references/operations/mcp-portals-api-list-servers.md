# GET /accounts/{account_id}/access/ai-controls/mcp/servers

**Resource:** [MCP Portal Servers](../resources/MCP-Portal-Servers.md)
**List MCP Servers**
**Operation ID:** `mcp-portals-api-list-servers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List objects |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
