# webhooks_rule

The branch protection rule. Includes a `name` and all the [branch protection settings](https://docs.github.com/github/administering-a-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#about-branch-protection-settings) applied to branches that match the name. Binary settings are boolean. Multi-level configurations are one of `off`, `non_admins`, or `everyone`. Actor and build lists are arrays of strings.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin_enforced` | boolean | Yes |  |
| `allow_deletions_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `allow_force_pushes_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `authorized_actor_names` | string[] | Yes |  |
| `authorized_actors_only` | boolean | Yes |  |
| `authorized_dismissal_actors_only` | boolean | Yes |  |
| `create_protected` | boolean | No |  |
| `created_at` | string (date-time) | Yes |  |
| `dismiss_stale_reviews_on_push` | boolean | Yes |  |
| `id` | integer | Yes |  |
| `ignore_approvals_from_contributors` | boolean | Yes |  |
| `linear_history_requirement_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `lock_branch_enforcement_level` | enum: off, non_admins, everyone | Yes | The enforcement level of the branch lock setting. `off` means the branch is not locked, `non_admins` means the branch is read-only for non_admins, and `everyone` means the branch is read-only for everyone. |
| `lock_allows_fork_sync` | boolean | No | Whether users can pull changes from upstream when the branch is locked. Set to `true` to allow users to pull changes from upstream when the branch is locked. This setting is only applicable for forks. |
| `merge_queue_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `name` | string | Yes |  |
| `pull_request_reviews_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `repository_id` | integer | Yes |  |
| `require_code_owner_review` | boolean | Yes |  |
| `require_last_push_approval` | boolean | No | Whether the most recent push must be approved by someone other than the person who pushed it |
| `required_approving_review_count` | integer | Yes |  |
| `required_conversation_resolution_level` | enum: off, non_admins, everyone | Yes |  |
| `required_deployments_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `required_status_checks` | string[] | Yes |  |
| `required_status_checks_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `signature_requirement_enforcement_level` | enum: off, non_admins, everyone | Yes |  |
| `strict_required_status_checks_policy` | boolean | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

