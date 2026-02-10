# APIEntitiesAnalyticsCodeReviewMergeRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `iid` | integer | No |  |
| `project_id` | integer | No |  |
| `title` | string | No |  |
| `description` | string | No |  |
| `state` | string | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `web_url` | string | No |  |
| `milestone` | [APIEntitiesMilestone](APIEntitiesMilestone.md) | No |  |
| `author` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `approved_by` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `notes_count` | integer | No |  |
| `review_time` | integer | No | Review time in hours |
| `diff_stats` | string | No |  |

