# Webhooks

This resource represents webhooks. Webhooks are calls sent to a URL when an event occurs in Jira for issues specified by a JQL query. Only Connect and OAuth 2.0 apps can register and manage webhooks. For more information, see [Webhooks](https://developer.atlassian.com/cloud/jira/platform/webhooks/#registering-a-webhook-via-the-jira-rest-api-for-connect-apps).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/webhook` | Get dynamic webhooks for app | [View](../operations/getDynamicWebhooksForApp.md) |
| POST | `/rest/api/3/webhook` | Register dynamic webhooks | [View](../operations/registerDynamicWebhooks.md) |
| DELETE | `/rest/api/3/webhook` | Delete webhooks by ID | [View](../operations/deleteWebhookById.md) |
| GET | `/rest/api/3/webhook/failed` | Get failed webhooks | [View](../operations/getFailedWebhooks.md) |
| PUT | `/rest/api/3/webhook/refresh` | Extend webhook life | [View](../operations/refreshWebhooks.md) |
