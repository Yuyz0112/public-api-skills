# GET /api/v4/projects/{id}/cluster_agents/{agent_id}/url_configurations

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**List agent url configurations**
**Operation ID:** `getApiV4ProjectsIdClusterAgentsAgentIdUrlConfigurations`

This feature was introduced in GitLab 17.4. List agent url configurations

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

[APIEntitiesClustersAgentUrlConfiguration](../schemas/APIEntitiesClustersAgentUrlConfiguration/APIEntitiesClustersAgentUrlConfiguration.md)

