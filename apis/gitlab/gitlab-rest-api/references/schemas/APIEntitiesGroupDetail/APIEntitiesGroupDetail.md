# APIEntitiesGroupDetail

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
| `shared_with_groups` | string | No |  |
| `runners_token` | string | No |  |
| `enabled_git_access_protocol` | string | No |  |
| `prevent_sharing_groups_outside_hierarchy` | string | No |  |
| `step_up_auth_required_oauth_provider` | string | No | OAuth provider required for step-up authentication. |
| `projects` | [APIEntitiesProject](APIEntitiesProject.md) | No |  |
| `shared_projects` | [APIEntitiesProject](APIEntitiesProject.md) | No |  |
| `shared_runners_minutes_limit` | string | No |  |
| `extra_shared_runners_minutes_limit` | string | No |  |
| `prevent_forking_outside_group` | string | No |  |
| `service_access_tokens_expiration_enforced` | string | No |  |
| `membership_lock` | string | No |  |
| `ip_restriction_ranges` | string | No |  |
| `allowed_email_domains_list` | string | No |  |
| `only_allow_merge_if_pipeline_succeeds` | string | No |  |
| `allow_merge_on_skipped_pipeline` | string | No |  |
| `only_allow_merge_if_all_discussions_are_resolved` | string | No |  |
| `unique_project_download_limit` | string | No |  |
| `unique_project_download_limit_interval_in_seconds` | string | No |  |
| `unique_project_download_limit_allowlist` | string | No |  |
| `unique_project_download_limit_alertlist` | string | No |  |
| `auto_ban_user_on_excessive_projects_download` | string | No |  |

