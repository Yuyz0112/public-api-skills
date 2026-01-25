# integration

GitHub apps are a new way to extend GitHub. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks. GitHub apps are first class actors within GitHub.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the GitHub app |
| `slug` | string | No | The slug name of the GitHub app |
| `node_id` | string | Yes |  |
| `client_id` | string | No |  |
| `owner` | any | Yes |  |
| `name` | string | Yes | The name of the GitHub app |
| `description` | string | Yes |  |
| `external_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `permissions` | object | Yes | The set of permissions for the GitHub app |
| `events` | string[] | Yes | The list of events for the GitHub app. Note that the `installation_target`, `security_advisory`, and `meta` events are not included because they are global events and not specific to an installation. |
| `installations_count` | integer | No | The number of installations associated with the GitHub app. Only returned when the integration is requesting details about itself. |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issues` | string | No |  |
| `checks` | string | No |  |
| `metadata` | string | No |  |
| `contents` | string | No |  |
| `deployments` | string | No |  |

