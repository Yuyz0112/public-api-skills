# POST /app/hook/deliveries/{delivery_id}/attempts

**Resource:** [apps](../resources/apps.md)
**Redeliver a delivery for an app webhook**
**Operation ID:** `apps/redeliver-webhook-delivery`

Redeliver a delivery for the webhook configured for a GitHub App.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |
| 400 | (reference) |
| 422 | (reference) |

