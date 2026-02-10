# APIEntitiesCiPipelineScheduleDetails

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `description` | string | No |  |
| `ref` | string | No |  |
| `cron` | string | No |  |
| `cron_timezone` | string | No |  |
| `next_run_at` | DateTime | No |  |
| `active` | Boolean | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `owner` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `inputs` | [APIEntitiesCiInput](APIEntitiesCiInput.md) | No |  |
| `last_pipeline` | [APIEntitiesCiPipelineBasic](APIEntitiesCiPipelineBasic.md) | No |  |
| `variables` | [APIEntitiesCiVariable](APIEntitiesCiVariable.md) | No |  |

