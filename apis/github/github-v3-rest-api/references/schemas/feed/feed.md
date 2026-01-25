# feed

Feed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timeline_url` | string | Yes |  |
| `user_url` | string | Yes |  |
| `current_user_public_url` | string | No |  |
| `current_user_url` | string | No |  |
| `current_user_actor_url` | string | No |  |
| `current_user_organization_url` | string | No |  |
| `current_user_organization_urls` | string[] | No |  |
| `security_advisories_url` | string | No |  |
| `repository_discussions_url` | string | No | A feed of discussions for a given repository. |
| `repository_discussions_category_url` | string | No | A feed of discussions for a given repository and category. |
| `_links` | object | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timeline` | [link-with-type](link-with-type.md) | Yes |  |
| `user` | [link-with-type](link-with-type.md) | Yes |  |
| `security_advisories` | [link-with-type](link-with-type.md) | No |  |
| `current_user` | [link-with-type](link-with-type.md) | No |  |
| `current_user_public` | [link-with-type](link-with-type.md) | No |  |
| `current_user_actor` | [link-with-type](link-with-type.md) | No |  |
| `current_user_organization` | [link-with-type](link-with-type.md) | No |  |
| `current_user_organizations` | link-with-type[] | No |  |
| `repository_discussions` | [link-with-type](link-with-type.md) | No |  |
| `repository_discussions_category` | [link-with-type](link-with-type.md) | No |  |

