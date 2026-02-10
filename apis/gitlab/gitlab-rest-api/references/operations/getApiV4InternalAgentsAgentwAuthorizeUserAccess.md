# GET /api/v4/internal/agents/agentw/authorize_user_access

**Resource:** [Workspaces](../resources/Workspaces.md)
**authorize_user_access**
**Operation ID:** `getApiV4InternalAgentsAgentwAuthorizeUserAccess`

Returns whether the user is authorized to access the workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workspace_host` | query | string | Yes | Host of the workspace being accessed |
| `user_id` | query | integer | Yes | User ID of the user accessing the workspace |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

