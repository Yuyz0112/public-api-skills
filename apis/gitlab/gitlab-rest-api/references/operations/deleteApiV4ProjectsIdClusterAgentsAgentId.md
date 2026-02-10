# DELETE /api/v4/projects/{id}/cluster_agents/{agent_id}

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Delete a registered agent**
**Operation ID:** `deleteApiV4ProjectsIdClusterAgentsAgentId`

This feature was introduced in GitLab 14.10. Deletes an existing agent registration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `agent_id` | path | integer | Yes | The ID of an agent |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

