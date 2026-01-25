# webhook-gollum

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pages` | object[] | Yes | The pages that were updated. |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `pages`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created, edited | Yes | The action that was performed on the page. Can be `created` or `edited`. |
| `html_url` | string (uri) | Yes | Points to the HTML wiki page. |
| `page_name` | string | Yes | The name of the page. |
| `sha` | string | Yes | The latest commit SHA of the page. |
| `summary` | string | Yes |  |
| `title` | string | Yes | The current page title. |

