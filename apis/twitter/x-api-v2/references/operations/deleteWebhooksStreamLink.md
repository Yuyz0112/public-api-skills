# DELETE /2/tweets/search/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete stream link**
**Operation ID:** `deleteWebhooksStreamLink`

Deletes a link from FilteredStream events to the given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The webhook ID to link to your FilteredStream ruleset. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[WebhookLinksDeleteResponse](../schemas/Webhook/WebhookLinksDeleteResponse.md)

## Security

- **BearerToken**
