# protected-branch-pull-request-review

Protected Branch Pull Request Review

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | No |  |
| `dismissal_restrictions` | object | No |  |
| `bypass_pull_request_allowances` | object | No | Allow specific users, teams, or apps to bypass pull request requirements. |
| `dismiss_stale_reviews` | boolean | Yes |  |
| `require_code_owner_reviews` | boolean | Yes |  |
| `required_approving_review_count` | integer | No |  |
| `require_last_push_approval` | boolean | No | Whether the most recent push must be approved by someone other than the person who pushed it. |

## Nested Fields

### `dismissal_restrictions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `users` | simple-user[] | No | The list of users with review dismissal access. |
| `teams` | team[] | No | The list of teams with review dismissal access. |
| `apps` | integration[] | No | The list of apps with review dismissal access. |
| `url` | string | No |  |
| `users_url` | string | No |  |
| `teams_url` | string | No |  |

### `bypass_pull_request_allowances`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `users` | simple-user[] | No | The list of users allowed to bypass pull request requirements. |
| `teams` | team[] | No | The list of teams allowed to bypass pull request requirements. |
| `apps` | integration[] | No | The list of apps allowed to bypass pull request requirements. |

