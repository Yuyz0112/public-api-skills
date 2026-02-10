# GET /api/v4/projects/{id}/cluster_agents/{agent_id}/url_configurations/{url_configuration_id}

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Get a single agent url configuration**
**Operation ID:** `getApiV4ProjectsIdClusterAgentsAgentIdUrlConfigurationsUrlConfigurationId`

This feature was introduced in GitLab 17.4. Gets a single agent url configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |
| `url_configuration_id` | path | integer | Yes | The ID of the agent url configuration |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesClustersAgentUrlConfiguration](../schemas/APIEntitiesClustersAgentUrlConfiguration/APIEntitiesClustersAgentUrlConfiguration.md)

