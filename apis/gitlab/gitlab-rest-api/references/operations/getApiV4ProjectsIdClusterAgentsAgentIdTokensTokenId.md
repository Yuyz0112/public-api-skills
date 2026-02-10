# GET /api/v4/projects/{id}/cluster_agents/{agent_id}/tokens/{token_id}

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Get a single agent token**
**Operation ID:** `getApiV4ProjectsIdClusterAgentsAgentIdTokensTokenId`

This feature was introduced in GitLab 15.0. Gets a single agent token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |
| `token_id` | path | integer | Yes | The ID of the agent token |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesClustersAgentToken](../schemas/APIEntitiesClustersAgentToken/APIEntitiesClustersAgentToken.md)

