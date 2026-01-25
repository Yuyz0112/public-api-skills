# Webhook

A webhook.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `events` | string[] | Yes | The Jira events that trigger the webhook. |
| `expirationDate` | integer (int64) | No | The date after which the webhook is no longer sent. Use [Extend webhook life](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-webhooks/#api-rest-api-3-webhook-refresh-put) to extend the date. |
| `fieldIdsFilter` | string[] | No | A list of field IDs. When the issue changelog contains any of the fields, the webhook `jira:issue_updated` is sent. If this parameter is not present, the app is notified about all field updates. |
| `id` | integer (int64) | Yes | The ID of the webhook. |
| `issuePropertyKeysFilter` | string[] | No | A list of issue property keys. A change of those issue properties triggers the `issue_property_set` or `issue_property_deleted` webhooks. If this parameter is not present, the app is notified about all issue property updates. |
| `jqlFilter` | string | Yes | The JQL filter that specifies which issues the webhook is sent for. |
| `url` | string | Yes | The URL that specifies where the webhooks are sent. |

