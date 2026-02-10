# APIEntitiesDeploymentExtended

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `iid` | integer | No |  |
| `ref` | string | No |  |
| `sha` | string | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `user` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `environment` | [APIEntitiesEnvironmentBasic](APIEntitiesEnvironmentBasic.md) | No |  |
| `deployable` | [APIEntitiesCiJob](APIEntitiesCiJob.md) | No |  |
| `status` | string | No |  |
| `pending_approval_count` | integer | No |  |
| `approvals` | [APIEntitiesDeploymentsApproval](APIEntitiesDeploymentsApproval.md) | No |  |
| `approval_summary` | [APIEntitiesDeploymentsApprovalSummary](APIEntitiesDeploymentsApprovalSummary.md) | No |  |

