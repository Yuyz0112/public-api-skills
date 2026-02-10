# APIEntitiesCiPipelineWithMetadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `iid` | integer | No |  |
| `project_id` | integer | No |  |
| `sha` | string | No |  |
| `ref` | string | No |  |
| `status` | string | No |  |
| `source` | string | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `web_url` | string | No |  |
| `before_sha` | string | No |  |
| `tag` | Boolean | No |  |
| `yaml_errors` | string | No |  |
| `user` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `started_at` | DateTime | No |  |
| `finished_at` | DateTime | No |  |
| `committed_at` | DateTime | No |  |
| `duration` | integer | No | Time spent running in seconds |
| `queued_duration` | integer | No | Time spent enqueued in seconds |
| `coverage` | number (float) | No |  |
| `detailed_status` | [DetailedStatusEntity](DetailedStatusEntity.md) | No |  |
| `archived` | Boolean | No |  |
| `name` | string | No |  |

