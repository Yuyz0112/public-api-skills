# APIEntitiesGroup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `web_url` | string | No |  |
| `name` | string | No |  |
| `path` | string | No |  |
| `description` | string | No |  |
| `visibility` | string | No |  |
| `share_with_group_lock` | string | No |  |
| `require_two_factor_authentication` | string | No |  |
| `two_factor_grace_period` | string | No |  |
| `project_creation_level` | string | No |  |
| `auto_devops_enabled` | string | No |  |
| `subgroup_creation_level` | string | No |  |
| `emails_disabled` | Boolean | No |  |
| `emails_enabled` | Boolean | No |  |
| `show_diff_preview_in_email` | Boolean | No |  |
| `mentions_disabled` | string | No |  |
| `lfs_enabled` | string | No |  |
| `archived` | Boolean | No |  |
| `math_rendering_limits_enabled` | Boolean | No |  |
| `lock_math_rendering_limits_enabled` | Boolean | No |  |
| `default_branch` | string | No |  |
| `default_branch_protection` | string | No |  |
| `default_branch_protection_defaults` | string | No |  |
| `avatar_url` | string | No |  |
| `request_access_enabled` | string | No |  |
| `full_name` | string | No |  |
| `full_path` | string | No |  |
| `created_at` | string | No |  |
| `parent_id` | string | No |  |
| `organization_id` | string | No |  |
| `shared_runners_setting` | string | No |  |
| `max_artifacts_size` | integer | No |  |
| `custom_attributes` | [APIEntitiesCustomAttribute](APIEntitiesCustomAttribute.md) | No |  |
| `statistics` | string | No |  |
| `marked_for_deletion_on` | string | No |  |
| `root_storage_statistics` | [APIEntitiesNamespaceRootStorageStatistics](APIEntitiesNamespaceRootStorageStatistics.md) | No |  |
| `ldap_cn` | string | No |  |
| `ldap_access` | string | No |  |
| `ldap_group_links` | [APIEntitiesLdapGroupLink](APIEntitiesLdapGroupLink.md) | No |  |
| `saml_group_links` | [APIEntitiesSamlGroupLink](APIEntitiesSamlGroupLink.md) | No |  |
| `file_template_project_id` | string | No |  |
| `wiki_access_level` | string | No |  |
| `repository_storage` | string | No |  |
| `duo_core_features_enabled` | Boolean | No | [Experimental] Indicates whether GitLab Duo Core features are enabled for the group |
| `duo_features_enabled` | string | No |  |
| `lock_duo_features_enabled` | string | No |  |
| `auto_duo_code_review_enabled` | string | No |  |
| `web_based_commit_signing_enabled` | string | No |  |
| `allow_personal_snippets` | string | No |  |
| `duo_namespace_access_rules` | string | No |  |

