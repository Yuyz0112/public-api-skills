# APIEntitiesMergeTrainsCar

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `merge_request` | [APIEntitiesMergeRequestSimple](APIEntitiesMergeRequestSimple.md) | No |  |
| `user` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `pipeline` | [APIEntitiesCiPipelineBasic](APIEntitiesCiPipelineBasic.md) | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `target_branch` | string | No |  |
| `status` | string | No |  |
| `merged_at` | DateTime | No |  |
| `duration` | integer | No | Time spent in seconds |

