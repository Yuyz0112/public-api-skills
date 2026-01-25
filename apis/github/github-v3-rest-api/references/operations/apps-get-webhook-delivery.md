# GET /app/hook/deliveries/{delivery_id}

**Resource:** [apps](../resources/apps.md)
**Get a delivery for an app webhook**
**Operation ID:** `apps/get-webhook-delivery`

Returns a delivery for the webhook configured for a GitHub App.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[hook-delivery](../schemas/hook-delivery/hook-delivery.md)

