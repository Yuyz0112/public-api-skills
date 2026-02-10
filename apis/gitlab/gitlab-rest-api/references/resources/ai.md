# ai

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v4/ai/third_party_agents/direct_access` | Get connection details so that third party agents can interact with AI Gateway | [View](../operations/postApiV4AiThirdPartyAgentsDirectAccess.md) |
| POST | `/api/v4/ai/duo_workflows/code_review/add_comments` | Add code review comments to a merge request | [View](../operations/postApiV4AiDuoWorkflowsCodeReviewAddComments.md) |
| POST | `/api/v4/ai/duo_workflows/revoke_token` | Revoke ai_workflows token | [View](../operations/postApiV4AiDuoWorkflowsRevokeToken.md) |
| GET | `/api/v4/ai/duo_workflows/workflows/{id}` |  | [View](../operations/getApiV4AiDuoWorkflowsWorkflowsId.md) |
| PATCH | `/api/v4/ai/duo_workflows/workflows/{id}` | Updates the workflow status | [View](../operations/patchApiV4AiDuoWorkflowsWorkflowsId.md) |
| GET | `/api/v4/ai/duo_workflows/workflows/{id}/checkpoints` |  | [View](../operations/getApiV4AiDuoWorkflowsWorkflowsIdCheckpoints.md) |
| POST | `/api/v4/ai/duo_workflows/workflows/{id}/checkpoints` |  | [View](../operations/postApiV4AiDuoWorkflowsWorkflowsIdCheckpoints.md) |
| GET | `/api/v4/ai/duo_workflows/workflows/{id}/checkpoints/{checkpoint_id}` |  | [View](../operations/getApiV4AiDuoWorkflowsWorkflowsIdCheckpointsCheckpointId.md) |
| POST | `/api/v4/ai/duo_workflows/workflows/{id}/checkpoint_writes_batch` |  | [View](../operations/postApiV4AiDuoWorkflowsWorkflowsIdCheckpointWritesBatch.md) |
| GET | `/api/v4/ai/duo_workflows/workflows/{id}/events` |  | [View](../operations/getApiV4AiDuoWorkflowsWorkflowsIdEvents.md) |
| POST | `/api/v4/ai/duo_workflows/workflows/{id}/events` |  | [View](../operations/postApiV4AiDuoWorkflowsWorkflowsIdEvents.md) |
| PUT | `/api/v4/ai/duo_workflows/workflows/{id}/events/{event_id}` |  | [View](../operations/putApiV4AiDuoWorkflowsWorkflowsIdEventsEventId.md) |
| POST | `/api/v4/ai/duo_workflows/direct_access` | Connection details for accessing Duo Agent Platform Service directly | [View](../operations/postApiV4AiDuoWorkflowsDirectAccess.md) |
| GET | `/api/v4/ai/duo_workflows/list_tools` | List Duo Agent Platform tools | [View](../operations/getApiV4AiDuoWorkflowsListTools.md) |
| GET | `/api/v4/ai/duo_workflows/ws` |  | [View](../operations/getApiV4AiDuoWorkflowsWs.md) |
| POST | `/api/v4/ai/duo_workflows/workflows` | creates workflow persistence | [View](../operations/postApiV4AiDuoWorkflowsWorkflows.md) |
| GET | `/api/v4/ai/duo_workflows/workflows/agent_privileges` | Get all possible agent privileges and descriptions | [View](../operations/getApiV4AiDuoWorkflowsWorkflowsAgentPrivileges.md) |
| POST | `/api/v4/ai/llm/git_command` | Generates Git commands from natural text | [View](../operations/postApiV4AiLlmGitCommand.md) |
