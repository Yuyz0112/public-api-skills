# organization-simple-webhooks

A GitHub organization. Webhook payloads contain the `organization` property when the webhook is configured for an
organization, or when the event occurs from activity in a repository owned by an organization.

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

