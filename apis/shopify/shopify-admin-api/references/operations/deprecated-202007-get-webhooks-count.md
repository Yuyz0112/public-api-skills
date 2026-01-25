# GET /admin/api/2020-07/webhooks/count.json

**Resource:** [events/webhook](../resources/events-webhook.md)
**Retrieves a count of existing webhook subscriptions**
**Operation ID:** `deprecated_202007_get_webhooks_count`

https://shopify.dev/docs/admin-api/rest/reference/events/webhook#count-2020-07

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `address` | query | any | No | Retrieve webhook subscriptions that send the POST request to this URI. |
| `topic` | query | any | No | Show webhook subscriptions with a given topic.
For a list of valid values, refer to the topic property.> |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

