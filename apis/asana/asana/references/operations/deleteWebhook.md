# DELETE /webhooks/{webhook_gid}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete a webhook**
**Operation ID:** `deleteWebhook`

<b>Required scope: </b><code>webhooks:delete</code>

This method *permanently* removes a webhook. Note that it may be possible to receive a request that was already in flight after deleting the webhook, but no further requests will be issued.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested webhook. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: webhooks:delete
