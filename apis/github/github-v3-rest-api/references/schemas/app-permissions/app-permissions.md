# app-permissions

The permissions granted to the user access token.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | enum: read, write | No | The level of permission to grant the access token for GitHub Actions workflows, workflow runs, and artifacts. |
| `administration` | enum: read, write | No | The level of permission to grant the access token for repository creation, deletion, settings, teams, and collaborators creation. |
| `artifact_metadata` | enum: read, write | No | The level of permission to grant the access token to create and retrieve build artifact metadata records. |
| `attestations` | enum: read, write | No | The level of permission to create and retrieve the access token for repository attestations. |
| `checks` | enum: read, write | No | The level of permission to grant the access token for checks on code. |
| `codespaces` | enum: read, write | No | The level of permission to grant the access token to create, edit, delete, and list Codespaces. |
| `contents` | enum: read, write | No | The level of permission to grant the access token for repository contents, commits, branches, downloads, releases, and merges. |
| `dependabot_secrets` | enum: read, write | No | The level of permission to grant the access token to manage Dependabot secrets. |
| `deployments` | enum: read, write | No | The level of permission to grant the access token for deployments and deployment statuses. |
| `discussions` | enum: read, write | No | The level of permission to grant the access token for discussions and related comments and labels. |
| `environments` | enum: read, write | No | The level of permission to grant the access token for managing repository environments. |
| `issues` | enum: read, write | No | The level of permission to grant the access token for issues and related comments, assignees, labels, and milestones. |
| `merge_queues` | enum: read, write | No | The level of permission to grant the access token to manage the merge queues for a repository. |
| `metadata` | enum: read, write | No | The level of permission to grant the access token to search repositories, list collaborators, and access repository metadata. |
| `packages` | enum: read, write | No | The level of permission to grant the access token for packages published to GitHub Packages. |
| `pages` | enum: read, write | No | The level of permission to grant the access token to retrieve Pages statuses, configuration, and builds, as well as create new builds. |
| `pull_requests` | enum: read, write | No | The level of permission to grant the access token for pull requests and related comments, assignees, labels, milestones, and merges. |
| `repository_custom_properties` | enum: read, write | No | The level of permission to grant the access token to view and edit custom properties for a repository, when allowed by the property. |
| `repository_hooks` | enum: read, write | No | The level of permission to grant the access token to manage the post-receive hooks for a repository. |
| `repository_projects` | enum: read, write, admin | No | The level of permission to grant the access token to manage repository projects, columns, and cards. |
| `secret_scanning_alerts` | enum: read, write | No | The level of permission to grant the access token to view and manage secret scanning alerts. |
| `secrets` | enum: read, write | No | The level of permission to grant the access token to manage repository secrets. |
| `security_events` | enum: read, write | No | The level of permission to grant the access token to view and manage security events like code scanning alerts. |
| `single_file` | enum: read, write | No | The level of permission to grant the access token to manage just a single file. |
| `statuses` | enum: read, write | No | The level of permission to grant the access token for commit statuses. |
| `vulnerability_alerts` | enum: read, write | No | The level of permission to grant the access token to manage Dependabot alerts. |
| `workflows` | enum: write | No | The level of permission to grant the access token to update GitHub Actions workflow files. |
| `custom_properties_for_organizations` | enum: read, write | No | The level of permission to grant the access token to view and edit custom properties for an organization, when allowed by the property. |
| `members` | enum: read, write | No | The level of permission to grant the access token for organization teams and members. |
| `organization_administration` | enum: read, write | No | The level of permission to grant the access token to manage access to an organization. |
| `organization_custom_roles` | enum: read, write | No | The level of permission to grant the access token for custom repository roles management. |
| `organization_custom_org_roles` | enum: read, write | No | The level of permission to grant the access token for custom organization roles management. |
| `organization_custom_properties` | enum: read, write, admin | No | The level of permission to grant the access token for repository custom properties management at the organization level. |
| `organization_copilot_seat_management` | enum: write | No | The level of permission to grant the access token for managing access to GitHub Copilot for members of an organization with a Copilot Business subscription. This property is in public preview and is subject to change. |
| `organization_announcement_banners` | enum: read, write | No | The level of permission to grant the access token to view and manage announcement banners for an organization. |
| `organization_events` | enum: read | No | The level of permission to grant the access token to view events triggered by an activity in an organization. |
| `organization_hooks` | enum: read, write | No | The level of permission to grant the access token to manage the post-receive hooks for an organization. |
| `organization_personal_access_tokens` | enum: read, write | No | The level of permission to grant the access token for viewing and managing fine-grained personal access token requests to an organization. |
| `organization_personal_access_token_requests` | enum: read, write | No | The level of permission to grant the access token for viewing and managing fine-grained personal access tokens that have been approved by an organization. |
| `organization_plan` | enum: read | No | The level of permission to grant the access token for viewing an organization's plan. |
| `organization_projects` | enum: read, write, admin | No | The level of permission to grant the access token to manage organization projects and projects public preview (where available). |
| `organization_packages` | enum: read, write | No | The level of permission to grant the access token for organization packages published to GitHub Packages. |
| `organization_secrets` | enum: read, write | No | The level of permission to grant the access token to manage organization secrets. |
| `organization_self_hosted_runners` | enum: read, write | No | The level of permission to grant the access token to view and manage GitHub Actions self-hosted runners available to an organization. |
| `organization_user_blocking` | enum: read, write | No | The level of permission to grant the access token to view and manage users blocked by the organization. |
| `team_discussions` | enum: read, write | No | The level of permission to grant the access token to manage team discussions and related comments. |
| `email_addresses` | enum: read, write | No | The level of permission to grant the access token to manage the email addresses belonging to a user. |
| `followers` | enum: read, write | No | The level of permission to grant the access token to manage the followers belonging to a user. |
| `git_ssh_keys` | enum: read, write | No | The level of permission to grant the access token to manage git SSH keys. |
| `gpg_keys` | enum: read, write | No | The level of permission to grant the access token to view and manage GPG keys belonging to a user. |
| `interaction_limits` | enum: read, write | No | The level of permission to grant the access token to view and manage interaction limits on a repository. |
| `profile` | enum: write | No | The level of permission to grant the access token to manage the profile settings belonging to a user. |
| `starring` | enum: read, write | No | The level of permission to grant the access token to list and manage repositories a user is starring. |
| `enterprise_custom_properties_for_organizations` | enum: read, write, admin | No | The level of permission to grant the access token for organization custom properties management at the enterprise level. |

