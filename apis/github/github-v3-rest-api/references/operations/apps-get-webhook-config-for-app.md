# GET /app/hook/config

**Resource:** [apps](../resources/apps.md)
**Get a webhook configuration for an app**
**Operation ID:** `apps/get-webhook-config-for-app`

Returns the webhook configuration for a GitHub App. For more information about configuring a webhook for your app, see "[Creating a GitHub App](/developers/apps/creating-a-github-app)."

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[webhook-config](../schemas/webhook-config/webhook-config.md)

