# APIEntitiesEnvironment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `name` | string | No |  |
| `slug` | string | No |  |
| `external_url` | string | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `tier` | string | No |  |
| `project` | [APIEntitiesBasicProjectDetails](APIEntitiesBasicProjectDetails.md) | No |  |
| `last_deployment` | [APIEntitiesDeployment](APIEntitiesDeployment.md) | No |  |
| `state` | string | No |  |
| `auto_stop_at` | DateTime | No |  |
| `cluster_agent` | [APIEntitiesClustersAgent](APIEntitiesClustersAgent.md) | No |  |
| `kubernetes_namespace` | string | No |  |
| `flux_resource_path` | string | No |  |
| `description` | string | No |  |
| `auto_stop_setting` | string | No |  |

