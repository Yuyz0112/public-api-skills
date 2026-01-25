# GET /rest/api/3/webhook

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get dynamic webhooks for app**
**Operation ID:** `getDynamicWebhooksForApp`

Returns a [paginated](#pagination) list of the webhooks registered by the calling app.

**[Permissions](#permissions) required:** Only [Connect](https://developer.atlassian.com/cloud/jira/platform/#connect-apps) and [OAuth 2.0](https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps) apps can use this operation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the caller isn't an app. |

**Success Response Schema:**

[PageBeanWebhook](../schemas/Page/PageBeanWebhook.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, manage:jira-webhook
