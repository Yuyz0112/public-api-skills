# GET /accounts/{account_id}/access/ai-controls/mcp/portals

**Resource:** [MCP Portal](../resources/MCP-Portal.md)
**List MCP Portals**
**Operation ID:** `mcp-portals-api-list-portals`

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
