# APIEntitiesCiJob

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `status` | string | No |  |
| `stage` | string | No |  |
| `name` | string | No |  |
| `ref` | string | No |  |
| `tag` | Boolean | No |  |
| `coverage` | number (float) | No |  |
| `allow_failure` | Boolean | No |  |
| `created_at` | DateTime | No |  |
| `started_at` | DateTime | No |  |
| `finished_at` | DateTime | No |  |
| `erased_at` | DateTime | No |  |
| `duration` | number (float) | No | Time spent running |
| `queued_duration` | number (float) | No | Time spent enqueued |
| `user` | [APIEntitiesUser](APIEntitiesUser.md) | No |  |
| `commit` | [APIEntitiesCommit](APIEntitiesCommit.md) | No |  |
| `pipeline` | [APIEntitiesCiPipelineBasic](APIEntitiesCiPipelineBasic.md) | No |  |
| `failure_reason` | string | No |  |
| `web_url` | string | No |  |
| `project` | string | No |  |
| `artifacts_file` | [APIEntitiesCiJobArtifactFile](APIEntitiesCiJobArtifactFile.md) | No |  |
| `artifacts` | APIEntitiesCiJobArtifact[] | No |  |
| `runner` | [APIEntitiesCiRunner](APIEntitiesCiRunner.md) | No |  |
| `runner_manager` | [APIEntitiesCiRunnerManager](APIEntitiesCiRunnerManager.md) | No |  |
| `artifacts_expire_at` | DateTime | No |  |
| `archived` | Boolean | No |  |
| `tag_list` | string[] | No |  |

