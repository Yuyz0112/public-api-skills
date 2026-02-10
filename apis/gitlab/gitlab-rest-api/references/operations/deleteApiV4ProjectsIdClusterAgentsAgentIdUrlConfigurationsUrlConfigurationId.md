# DELETE /api/v4/projects/{id}/cluster_agents/{agent_id}/url_configurations/{url_configuration_id}

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Delete an agent url configuration**
**Operation ID:** `deleteApiV4ProjectsIdClusterAgentsAgentIdUrlConfigurationsUrlConfigurationId`

This feature was introduced in GitLab 17.4. Deletes an agent url configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |
| `url_configuration_id` | path | integer | Yes | The ID of the agent url configuration |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

