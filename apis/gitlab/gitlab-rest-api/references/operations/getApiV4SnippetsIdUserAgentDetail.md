# GET /api/v4/snippets/{id}/user_agent_detail

**Resource:** [Snippets](../resources/Snippets.md)
**Get the user agent details for a snippet**
**Operation ID:** `getApiV4SnippetsIdUserAgentDetail`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a snippet |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesUserAgentDetail](../schemas/APIEntitiesUserAgentDetail/APIEntitiesUserAgentDetail.md)

