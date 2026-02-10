# DELETE /api/v4/projects/{id}/cluster_agents/{agent_id}/tokens/{token_id}

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Revoke an agent token**
**Operation ID:** `deleteApiV4ProjectsIdClusterAgentsAgentIdTokensTokenId`

This feature was introduced in GitLab 15.0. Revokes an agent token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |
| `token_id` | path | integer | Yes | The ID of the agent token |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

