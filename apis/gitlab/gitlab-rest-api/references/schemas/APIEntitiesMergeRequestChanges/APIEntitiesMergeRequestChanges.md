# APIEntitiesMergeRequestChanges

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
| `merged_by` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `merge_user` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `merged_at` | string | No |  |
| `closed_by` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `closed_at` | string | No |  |
| `title_html` | string | No |  |
| `description_html` | string | No |  |
| `target_branch` | string | No |  |
| `source_branch` | string | No |  |
| `user_notes_count` | string | No |  |
| `upvotes` | string | No |  |
| `downvotes` | string | No |  |
| `author` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `assignees` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `assignee` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `reviewers` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `source_project_id` | string | No |  |
| `target_project_id` | string | No |  |
| `labels` | string | No |  |
| `draft` | string | No |  |
| `imported` | string | No |  |
| `imported_from` | string | No |  |
| `work_in_progress` | string | No |  |
| `milestone` | [APIEntitiesMilestone](APIEntitiesMilestone.md) | No |  |
| `merge_when_pipeline_succeeds` | string | No |  |
| `merge_status` | string | No |  |
| `detailed_merge_status` | string | No |  |
| `merge_after` | string | No |  |
| `sha` | string | No |  |
| `merge_commit_sha` | string | No |  |
| `squash_commit_sha` | string | No |  |
| `discussion_locked` | string | No |  |
| `should_remove_source_branch` | string | No |  |
| `force_remove_source_branch` | string | No |  |
| `prepared_at` | string | No |  |
| `allow_collaboration` | string | No |  |
| `allow_maintainer_to_push` | string | No |  |
| `reference` | string | No |  |
| `references` | [APIEntitiesIssuableReferences](APIEntitiesIssuableReferences.md) | No |  |
| `web_url` | string | No |  |
| `time_stats` | [APIEntitiesIssuableTimeStats](APIEntitiesIssuableTimeStats.md) | No |  |
| `squash` | string | No |  |
| `squash_on_merge` | string | No |  |
| `task_completion_status` | string | No |  |
| `has_conflicts` | string | No |  |
| `blocking_discussions_resolved` | string | No |  |
| `approvals_before_merge` | string | No |  |
| `subscribed` | string | No |  |
| `changes_count` | string | No |  |
| `latest_build_started_at` | string | No |  |
| `latest_build_finished_at` | string | No |  |
| `first_deployed_to_production_at` | string | No |  |
| `pipeline` | [APIEntitiesCiPipelineBasic](APIEntitiesCiPipelineBasic.md) | No |  |
| `head_pipeline` | [APIEntitiesCiPipeline](APIEntitiesCiPipeline.md) | No |  |
| `diff_refs` | [APIEntitiesDiffRefs](APIEntitiesDiffRefs.md) | No |  |
| `merge_error` | string | No |  |
| `rebase_in_progress` | string | No |  |
| `diverged_commits_count` | string | No |  |
| `first_contribution` | string | No |  |
| `user` | string | No |  |
| `changes` | [APIEntitiesDiff](APIEntitiesDiff.md) | No |  |
| `overflow` | string | No |  |

