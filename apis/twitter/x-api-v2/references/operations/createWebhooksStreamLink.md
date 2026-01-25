# POST /2/tweets/search/webhooks/{webhook_id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Create stream link**
**Operation ID:** `createWebhooksStreamLink`

Creates a link to deliver FilteredStream events to the given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The webhook ID to link to your FilteredStream ruleset. |
| `tweet.fields` | query | string | No | A comma separated list of Tweet fields to display. |
| `expansions` | query | string | No | A comma separated list of fields to expand. |
| `media.fields` | query | string | No | A comma separated list of Media fields to display. |
| `poll.fields` | query | string | No | A comma separated list of Poll fields to display. |
| `user.fields` | query | string | No | A comma separated list of User fields to display. |
| `place.fields` | query | string | No | A comma separated list of Place fields to display. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[WebhookLinksCreateResponse](../schemas/Webhook/WebhookLinksCreateResponse.md)

## Security

- **BearerToken**
