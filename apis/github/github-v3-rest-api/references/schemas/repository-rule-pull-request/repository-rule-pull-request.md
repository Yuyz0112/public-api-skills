# repository-rule-pull-request

Require all commits be made to a non-target branch and submitted via a pull request before they can be merged.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: pull_request | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_merge_methods` | string[] | No | Array of allowed merge methods. Allowed values include `merge`, `squash`, and `rebase`. At least one option must be enabled. |
| `dismiss_stale_reviews_on_push` | boolean | Yes | New, reviewable commits pushed will dismiss previous pull request review approvals. |
| `require_code_owner_review` | boolean | Yes | Require an approving review in pull requests that modify files that have a designated code owner. |
| `require_last_push_approval` | boolean | Yes | Whether the most recent reviewable push must be approved by someone other than the person who pushed it. |
| `required_approving_review_count` | integer | Yes | The number of approving reviews that are required before a pull request can be merged. |
| `required_review_thread_resolution` | boolean | Yes | All conversations on code must be resolved before a pull request can be merged. |
| `required_reviewers` | repository-rule-params-required-reviewer-configuration[] | No | > [!NOTE]
> `required_reviewers` is in beta and subject to change.

A collection of reviewers and associated file patterns. Each reviewer has a list of file patterns which determine the files that reviewer is required to review. |

