# GET /admin/api/2020-07/webhooks.json

**Resource:** [events/webhook](../resources/events-webhook.md)
**Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202007_get_webhooks`

https://shopify.dev/docs/admin-api/rest/reference/events/webhook#index-2020-07

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `address` | query | any | No | Retrieve webhook subscriptions that send the POST request to this URI. |
| `created_at_max` | query | any | No | Retrieve webhook subscriptions that were created before a given date and time (format: 2014-04-25T16:15:47-04:00). |
| `created_at_min` | query | any | No | Retrieve webhook subscriptions that were created after a given date and time (format: 2014-04-25T16:15:47-04:00). |
| `fields` | query | any | No | Comma-separated list of the properties you want returned for each item in the result list. Use this parameter to restrict the returned list of items to only those properties you specify. |
| `limit` | query | any | No | Maximum number of webhook subscriptions that should be returned. Setting this parameter outside the maximum range will return an error.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict the returned list to webhook subscriptions whose id is greater than the specified since_id. |
| `topic` | query | any | No | Show webhook subscriptions with a given topic.
For a list of valid values, refer to the topic property.> |
| `updated_at_min` | query | any | No | Retrieve webhooks that were updated before a given date and time (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Retrieve webhooks that were updated after a given date and time (format: 2014-04-25T16:15:47-04:00). |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

