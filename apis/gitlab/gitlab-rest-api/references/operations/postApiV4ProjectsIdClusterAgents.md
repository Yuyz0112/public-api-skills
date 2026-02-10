# POST /api/v4/projects/{id}/cluster_agents

**Resource:** [Cluster agents](../resources/Cluster-agents.md)
**Register an agent with a project**
**Operation ID:** `postApiV4ProjectsIdClusterAgents`

This feature was introduced in GitLab 14.10. Registers an agent to the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesClustersAgent](../schemas/APIEntitiesClustersAgent/APIEntitiesClustersAgent.md)

