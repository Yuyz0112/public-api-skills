# GET /api/v4/ai/duo_workflows/list_tools

**Resource:** [ai](../resources/ai.md)
**List Duo Agent Platform tools**
**Operation ID:** `getApiV4AiDuoWorkflowsListTools`

This feature is experimental.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_definition` | query | string | No | workflow type based on its capability |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |
| 429 | Too many requests |

