# POST /api/v4/projects/{id}/cluster_agents/{agent_id}/url_configurations

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Create an agent url configuration for a receptive agent**
**Operation ID:** `postApiV4ProjectsIdClusterAgentsAgentIdUrlConfigurations`

This feature was introduced in GitLab 17.4. Creates a new url configuration for a receptive agent.

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

[APIEntitiesClustersAgentUrlConfiguration](../schemas/APIEntitiesClustersAgentUrlConfiguration/APIEntitiesClustersAgentUrlConfiguration.md)

