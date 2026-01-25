# organization-full

Organization Full

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
| `type` | string | Yes |  |
| `total_private_repos` | integer | No |  |
| `owned_private_repos` | integer | No |  |
| `private_gists` | integer | No |  |
| `disk_usage` | integer | No |  |
| `collaborators` | integer | No | The number of collaborators on private repositories.

This field may be null if the number of private repositories is over 50,000. |
| `billing_email` | string (email) | No |  |
| `plan` | object | No |  |
| `default_repository_permission` | string | No |  |
| `default_repository_branch` | string | No | The default branch for repositories created in this organization. |
| `members_can_create_repositories` | boolean | No |  |
| `two_factor_requirement_enabled` | boolean | No |  |
| `members_allowed_repository_creation_type` | string | No |  |
| `members_can_create_public_repositories` | boolean | No |  |
| `members_can_create_private_repositories` | boolean | No |  |
| `members_can_create_internal_repositories` | boolean | No |  |
| `members_can_create_pages` | boolean | No |  |
| `members_can_create_public_pages` | boolean | No |  |
| `members_can_create_private_pages` | boolean | No |  |
| `members_can_delete_repositories` | boolean | No |  |
| `members_can_change_repo_visibility` | boolean | No |  |
| `members_can_invite_outside_collaborators` | boolean | No |  |
| `members_can_delete_issues` | boolean | No |  |
| `display_commenter_full_name_setting_enabled` | boolean | No |  |
| `readers_can_create_discussions` | boolean | No |  |
| `members_can_create_teams` | boolean | No |  |
| `members_can_view_dependency_insights` | boolean | No |  |
| `members_can_fork_private_repositories` | boolean | No |  |
| `web_commit_signoff_required` | boolean | No |  |
| `advanced_security_enabled_for_new_repositories` | boolean | No | **Endpoint closing down notice.** Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead.

Whether GitHub Advanced Security is enabled for new repositories and repositories transferred to this organization.

This field is only visible to organization owners or members of a team with the security manager role. |
| `dependabot_alerts_enabled_for_new_repositories` | boolean | No | **Endpoint closing down notice.** Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead.

Whether Dependabot alerts are automatically enabled for new repositories and repositories transferred to this organization.

This field is only visible to organization owners or members of a team with the security manager role. |
| `dependabot_security_updates_enabled_for_new_repositories` | boolean | No | **Endpoint closing down notice.** Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead.

Whether Dependabot security updates are automatically enabled for new repositories and repositories transferred to this organization.

This field is only visible to organization owners or members of a team with the security manager role. |
| `dependency_graph_enabled_for_new_repositories` | boolean | No | **Endpoint closing down notice.** Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead.

Whether dependency graph is automatically enabled for new repositories and repositories transferred to this organization.

This field is only visible to organization owners or members of a team with the security manager role. |
| `secret_scanning_enabled_for_new_repositories` | boolean | No | **Endpoint closing down notice.** Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead.

Whether secret scanning is automatically enabled for new repositories and repositories transferred to this organization.

This field is only visible to organization owners or members of a team with the security manager role. |
| `secret_scanning_push_protection_enabled_for_new_repositories` | boolean | No | **Endpoint closing down notice.** Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead.

Whether secret scanning push protection is automatically enabled for new repositories and repositories transferred to this organization.

This field is only visible to organization owners or members of a team with the security manager role. |
| `secret_scanning_push_protection_custom_link_enabled` | boolean | No | Whether a custom link is shown to contributors who are blocked from pushing a secret by push protection. |
| `secret_scanning_push_protection_custom_link` | string | No | An optional URL string to display to contributors who are blocked from pushing a secret. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `archived_at` | string (date-time) | Yes |  |
| `deploy_keys_enabled_for_repositories` | boolean | No | Controls whether or not deploy keys may be added and used for repositories in the organization. |

## Nested Fields

### `plan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `space` | integer | Yes |  |
| `private_repos` | integer | Yes |  |
| `filled_seats` | integer | No |  |
| `seats` | integer | No |  |

