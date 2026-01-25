# enterprise-webhooks

An enterprise on GitHub. Webhook payloads contain the `enterprise` property when the webhook is configured
on an enterprise account or an organization that's part of an enterprise account. For more information,
see "[About enterprise accounts](https://docs.github.com/admin/overview/about-enterprise-accounts)."

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | A short description of the enterprise. |
| `html_url` | string (uri) | Yes |  |
| `website_url` | string (uri) | No | The enterprise's website URL. |
| `id` | integer | Yes | Unique identifier of the enterprise |
| `node_id` | string | Yes |  |
| `name` | string | Yes | The name of the enterprise. |
| `slug` | string | Yes | The slug url identifier for the enterprise. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `avatar_url` | string (uri) | Yes |  |

