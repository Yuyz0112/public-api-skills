# POST /accounts/{account_id}/access/ai-controls/mcp/servers

**Resource:** [MCP Portal Servers](../resources/MCP-Portal-Servers.md)
**Create a new MCP Server**
**Operation ID:** `mcp-portals-api-create-servers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returns the created Object |
| 400 | Input Validation Error |

## Security

- **api_token**
- **api_email**
- **api_key**
