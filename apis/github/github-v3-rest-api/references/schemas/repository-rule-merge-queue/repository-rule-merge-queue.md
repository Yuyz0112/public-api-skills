# repository-rule-merge-queue

Merges must be performed via a merge queue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: merge_queue | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `check_response_timeout_minutes` | integer | Yes | Maximum time for a required status check to report a conclusion. After this much time has elapsed, checks that have not reported a conclusion will be assumed to have failed |
| `grouping_strategy` | enum: ALLGREEN, HEADGREEN | Yes | When set to ALLGREEN, the merge commit created by merge queue for each PR in the group must pass all required checks to merge. When set to HEADGREEN, only the commit at the head of the merge group, i.e. the commit containing changes from all of the PRs in the group, must pass its required checks to merge. |
| `max_entries_to_build` | integer | Yes | Limit the number of queued pull requests requesting checks and workflow runs at the same time. |
| `max_entries_to_merge` | integer | Yes | The maximum number of PRs that will be merged together in a group. |
| `merge_method` | enum: MERGE, SQUASH, REBASE | Yes | Method to use when merging changes from queued pull requests. |
| `min_entries_to_merge` | integer | Yes | The minimum number of PRs that will be merged together in a group. |
| `min_entries_to_merge_wait_minutes` | integer | Yes | The time merge queue should wait after the first PR is added to the queue for the minimum group size to be met. After this time has elapsed, the minimum group size will be ignored and a smaller group will be merged. |

