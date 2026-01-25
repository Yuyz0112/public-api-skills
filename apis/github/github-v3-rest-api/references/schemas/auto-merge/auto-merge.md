# auto-merge

The status of auto merging a pull request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled_by` | [simple-user](simple-user.md) | Yes |  |
| `merge_method` | enum: merge, squash, rebase | Yes | The merge method to use. |
| `commit_title` | string | Yes | Title for the merge commit message. |
| `commit_message` | string | Yes | Commit message for the merge commit. |

