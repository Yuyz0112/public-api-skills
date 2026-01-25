# team-organization

Team Organization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | Yes |  |
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `repos_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `hooks_url` | string | Yes |  |
| `issues_url` | string | Yes |  |
| `members_url` | string | Yes |  |
| `public_members_url` | string | Yes |  |
| `avatar_url` | string | Yes |  |
| `description` | string | Yes |  |
| `name` | string | No |  |
| `company` | string | No |  |
| `blog` | string (uri) | No |  |
| `location` | string | No |  |
| `email` | string (email) | No |  |
| `twitter_username` | string | No |  |
| `is_verified` | boolean | No |  |
| `has_organization_projects` | boolean | Yes |  |
| `has_repository_projects` | boolean | Yes |  |
| `public_repos` | integer | Yes |  |
| `public_gists` | integer | Yes |  |
| `followers` | integer | Yes |  |
| `following` | integer | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `type` | string | Yes |  |
| `total_private_repos` | integer | No |  |
| `owned_private_repos` | integer | No |  |
| `private_gists` | integer | No |  |
| `disk_usage` | integer | No |  |
| `collaborators` | integer | No |  |
| `billing_email` | string (email) | No |  |
| `plan` | object | No |  |
| `default_repository_permission` | string | No |  |
| `members_can_create_repositories` | boolean | No |  |
| `two_factor_requirement_enabled` | boolean | No |  |
| `members_allowed_repository_creation_type` | string | No |  |
| `members_can_create_public_repositories` | boolean | No |  |
| `members_can_create_private_repositories` | boolean | No |  |
| `members_can_create_internal_repositories` | boolean | No |  |
| `members_can_create_pages` | boolean | No |  |
| `members_can_create_public_pages` | boolean | No |  |
| `members_can_create_private_pages` | boolean | No |  |
| `members_can_fork_private_repositories` | boolean | No |  |
| `web_commit_signoff_required` | boolean | No |  |
| `updated_at` | string (date-time) | Yes |  |
| `archived_at` | string (date-time) | Yes |  |

## Nested Fields

### `plan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `space` | integer | Yes |  |
| `private_repos` | integer | Yes |  |
| `filled_seats` | integer | No |  |
| `seats` | integer | No |  |

