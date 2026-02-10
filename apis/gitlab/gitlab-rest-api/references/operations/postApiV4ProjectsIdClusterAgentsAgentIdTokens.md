# POST /api/v4/projects/{id}/cluster_agents/{agent_id}/tokens

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Create an agent token**
**Operation ID:** `postApiV4ProjectsIdClusterAgentsAgentIdTokens`

This feature was introduced in GitLab 15.0. Creates a new token for an agent.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesClustersAgentTokenWithToken](../schemas/APIEntitiesClustersAgentTokenWithToken/APIEntitiesClustersAgentTokenWithToken.md)

