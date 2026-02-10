# APIEntitiesGroupPushRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `created_at` | DateTime | No |  |
| `commit_message_regex` | string | No |  |
| `commit_message_negative_regex` | string | No |  |
| `branch_name_regex` | string | No |  |
| `author_email_regex` | string | No |  |
| `file_name_regex` | string | No |  |
| `deny_delete_tag` | Boolean | No |  |
| `member_check` | Boolean | No |  |
| `prevent_secrets` | Boolean | No |  |
| `max_file_size` | integer | No |  |
| `commit_committer_check` | Boolean | No |  |
| `commit_committer_name_check` | Boolean | No |  |
| `reject_unsigned_commits` | Boolean | No |  |
| `reject_non_dco_commits` | Boolean | No |  |

