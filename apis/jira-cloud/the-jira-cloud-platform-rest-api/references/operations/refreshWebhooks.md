# PUT /rest/api/3/webhook/refresh

**Resource:** [Webhooks](../resources/Webhooks.md)
**Extend webhook life**
**Operation ID:** `refreshWebhooks`

Extends the life of webhook. Webhooks registered through the REST API expire after 30 days. Call this operation to keep them alive.

Unrecognized webhook IDs (those that are not found or belong to other apps) are ignored.

**[Permissions](#permissions) required:** Only [Connect](https://developer.atlassian.com/cloud/jira/platform/#connect-apps) and [OAuth 2.0](https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps) apps can use this operation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ContainerForWebhookIDs](../schemas/Container/ContainerForWebhookIDs.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the caller isn't an app. |

**Success Response Schema:**

[WebhooksExpirationDate](../schemas/Webhooks/WebhooksExpirationDate.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, manage:jira-webhook
