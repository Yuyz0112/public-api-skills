# GET /rest/api/3/webhook/failed

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get failed webhooks**
**Operation ID:** `getFailedWebhooks`

Returns webhooks that have recently failed to be delivered to the requesting app after the maximum number of retries.

After 72 hours the failure may no longer be returned by this operation.

The oldest failure is returned first.

This method uses a cursor-based pagination. To request the next page use the failure time of the last webhook on the list as the `failedAfter` value or use the URL provided in `next`.

**[Permissions](#permissions) required:** Only [Connect apps](https://developer.atlassian.com/cloud/jira/platform/index/#connect-apps) can use this operation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `maxResults` | query | integer (int32) | No | The maximum number of webhooks to return per page. If obeying the maxResults directive would result in records with the same failure time being split across pages, the directive is ignored and all records with the same failure time included on the page. |
| `after` | query | integer (int64) | No | The time after which any webhook failure must have occurred for the record to be returned, expressed as milliseconds since the UNIX epoch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | 400 response |
| 403 | Returned if the caller is not a Connect app. |

**Success Response Schema:**

[FailedWebhooks](../schemas/Failed/FailedWebhooks.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, manage:jira-webhook
