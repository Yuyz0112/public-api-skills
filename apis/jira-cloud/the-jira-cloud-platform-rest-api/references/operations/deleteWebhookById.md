# DELETE /rest/api/3/webhook

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete webhooks by ID**
**Operation ID:** `deleteWebhookById`

Removes webhooks by ID. Only webhooks registered by the calling app are removed. If webhooks created by other apps are specified, they are ignored.

**[Permissions](#permissions) required:** Only [Connect](https://developer.atlassian.com/cloud/jira/platform/#connect-apps) and [OAuth 2.0](https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps) apps can use this operation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ContainerForWebhookIDs](../schemas/Container/ContainerForWebhookIDs.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Returned if the request is successful. |
| 400 | Returned if the list of webhook IDs is missing. |
| 403 | Returned if the caller isn't an app. |

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, manage:jira-webhook
