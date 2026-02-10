# APIEntitiesIssueBasic

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
| `closed_at` | DateTime | No |  |
| `closed_by` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `labels` | string[] | No |  |
| `milestone` | [APIEntitiesMilestone](APIEntitiesMilestone.md) | No |  |
| `assignees` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `author` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `type` | string | No | One of ["ISSUE", "INCIDENT", "TEST_CASE", "REQUIREMENT", "TASK", "TICKET"] |
| `assignee` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `user_notes_count` | string | No |  |
| `merge_requests_count` | string | No |  |
| `upvotes` | string | No |  |
| `downvotes` | string | No |  |
| `start_date` | string | No |  |
| `due_date` | string | No |  |
| `confidential` | Boolean | No |  |
| `discussion_locked` | Boolean | No |  |
| `issue_type` | string | No |  |
| `web_url` | string | No |  |
| `time_stats` | [APIEntitiesIssuableTimeStats](APIEntitiesIssuableTimeStats.md) | No |  |
| `task_completion_status` | string | No |  |
| `weight` | string | No |  |
| `blocking_issues_count` | string | No |  |

