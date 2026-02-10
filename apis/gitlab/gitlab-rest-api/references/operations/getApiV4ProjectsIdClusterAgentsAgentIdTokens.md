# GET /api/v4/projects/{id}/cluster_agents/{agent_id}/tokens

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**List tokens for an agent**
**Operation ID:** `getApiV4ProjectsIdClusterAgentsAgentIdTokens`

This feature was introduced in GitLab 15.0. Returns a list of tokens for an agent.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesClustersAgentTokenBasic](../schemas/APIEntitiesClustersAgentTokenBasic/APIEntitiesClustersAgentTokenBasic.md)

