# simple-installation

The GitHub App installation. Webhook payloads contain the `installation` property when the event is configured
for and sent to a GitHub App. For more information,
see "[Using webhooks with GitHub Apps](https://docs.github.com/apps/creating-github-apps/registering-a-github-app/using-webhooks-with-github-apps)."

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the installation. |
| `node_id` | string | Yes | The global node ID of the installation. |

