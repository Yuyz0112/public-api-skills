# POST /rest/api/3/webhook

**Resource:** [Webhooks](../resources/Webhooks.md)
**Register dynamic webhooks**
**Operation ID:** `registerDynamicWebhooks`

Registers webhooks.

**NOTE:** for non-public OAuth apps, webhooks are delivered only if there is a match between the app owner and the user who registered a dynamic webhook.

**[Permissions](#permissions) required:** Only [Connect](https://developer.atlassian.com/cloud/jira/platform/#connect-apps) and [OAuth 2.0](https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps) apps can use this operation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WebhookRegistrationDetails](../schemas/Webhook/WebhookRegistrationDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the caller isn't an app. |

**Success Response Schema:**

[ContainerForRegisteredWebhooks](../schemas/Container/ContainerForRegisteredWebhooks.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, manage:jira-webhook
