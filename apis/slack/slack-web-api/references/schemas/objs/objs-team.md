# objs_team

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archived` | boolean | No |  |
| `avatar_base_url` | string (uri) | No |  |
| `created` | integer | No |  |
| `date_create` | integer | No |  |
| `deleted` | boolean | No |  |
| `description` | string | No |  |
| `discoverable` | any | No |  |
| `domain` | string | Yes |  |
| `email_domain` | string | Yes |  |
| `enterprise_id` | [defs_enterprise_id](defs-enterprise-id.md) | No |  |
| `enterprise_name` | [defs_enterprise_name](defs-enterprise-name.md) | No |  |
| `external_org_migrations` | [objs_external_org_migrations](objs-external-org-migrations.md) | No |  |
| `has_compliance_export` | boolean | No |  |
| `icon` | [objs_icon](objs-icon.md) | Yes |  |
| `id` | [defs_workspace_id](defs-workspace-id.md) | Yes |  |
| `is_assigned` | boolean | No |  |
| `is_enterprise` | integer | No |  |
| `is_over_storage_limit` | boolean | No |  |
| `limit_ts` | integer | No |  |
| `locale` | string | No |  |
| `messages_count` | integer | No |  |
| `msg_edit_window_mins` | integer | No |  |
| `name` | string | Yes |  |
| `over_integrations_limit` | boolean | No |  |
| `over_storage_limit` | boolean | No |  |
| `pay_prod_cur` | string | No |  |
| `plan` | enum: , std, plus... | No |  |
| `primary_owner` | [objs_primary_owner](objs-primary-owner.md) | No |  |
| `sso_provider` | object | No |  |

## Nested Fields

### `sso_provider`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | No |  |
| `name` | string | No |  |
| `type` | string | No |  |

