# GET /api/v4/projects/{id}/cluster_agents/{agent_id}

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Get details about an agent**
**Operation ID:** `getApiV4ProjectsIdClusterAgentsAgentId`

This feature was introduced in GitLab 14.10. Gets a single agent details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesClustersAgent](../schemas/APIEntitiesClustersAgent/APIEntitiesClustersAgent.md)

