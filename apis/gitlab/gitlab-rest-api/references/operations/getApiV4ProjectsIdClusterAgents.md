# GET /api/v4/projects/{id}/cluster_agents

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**List the agents for a project**
**Operation ID:** `getApiV4ProjectsIdClusterAgents`

This feature was introduced in GitLab 14.10. Returns the list of agents registered for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesClustersAgent](../schemas/APIEntitiesClustersAgent/APIEntitiesClustersAgent.md)

