# APIEntitiesProjectDetails

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `description` | string | No |  |
| `name` | string | No |  |
| `name_with_namespace` | string | No |  |
| `path` | string | No |  |
| `path_with_namespace` | string | No |  |
| `created_at` | DateTime | No |  |
| `default_branch` | string | No |  |
| `tag_list` | string[] | No |  |
| `topics` | string[] | No |  |
| `ssh_url_to_repo` | string | No |  |
| `http_url_to_repo` | string | No |  |
| `web_url` | string | No |  |
| `readme_url` | string | No |  |
| `forks_count` | integer | No |  |
| `license_url` | string | No |  |
| `license` | [APIEntitiesLicenseBasic](APIEntitiesLicenseBasic.md) | No |  |
| `avatar_url` | string | No |  |
| `star_count` | integer | No |  |
| `last_activity_at` | DateTime | No |  |
| `visibility` | string | No |  |
| `namespace` | [APIEntitiesNamespaceBasic](APIEntitiesNamespaceBasic.md) | No |  |
| `custom_attributes` | [APIEntitiesCustomAttribute](APIEntitiesCustomAttribute.md) | No |  |
| `repository_storage` | string | No |  |
| `forked_from_project` | [APIEntitiesBasicProjectDetails](APIEntitiesBasicProjectDetails.md) | No |  |

