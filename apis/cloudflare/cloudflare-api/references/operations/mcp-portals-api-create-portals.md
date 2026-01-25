# POST /accounts/{account_id}/access/ai-controls/mcp/portals

**Resource:** [MCP Portal](../resources/MCP-Portal.md)
**Create a new MCP Portal**
**Operation ID:** `mcp-portals-api-create-portals`

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
