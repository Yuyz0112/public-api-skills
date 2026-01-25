# GET /app/hook/deliveries

**Resource:** [apps](../resources/apps.md)
**List deliveries for an app webhook**
**Operation ID:** `apps/list-webhook-deliveries`

Returns a list of webhook deliveries for the webhook configured for a GitHub App.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [hook-delivery-item](../schemas/hook-delivery-item/hook-delivery-item.md)

