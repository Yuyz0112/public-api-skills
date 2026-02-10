# APIEntitiesProjectPushRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `project_id` | integer | No |  |
| `created_at` | date-time | No |  |
| `commit_message_regex` | string | No |  |
| `commit_message_negative_regex` | string | No |  |
| `branch_name_regex` | string | No |  |
| `deny_delete_tag` | Boolean | No |  |
| `member_check` | Boolean | No |  |
| `prevent_secrets` | Boolean | No |  |
| `author_email_regex` | string | No |  |
| `file_name_regex` | string | No |  |
| `max_file_size` | integer | No |  |
| `commit_committer_check` | boolean | No |  |
| `commit_committer_name_check` | boolean | No |  |
| `reject_unsigned_commits` | boolean | No |  |
| `reject_non_dco_commits` | boolean | No |  |

