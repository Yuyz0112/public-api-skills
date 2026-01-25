# WebhookV2

A description of an HTTP webhook (from Figma back to your application)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the webhook |
| `event_type` | [WebhookV2Event](WebhookV2Event.md) | Yes |  |
| `team_id` | string | Yes | The team id you are subscribed to for updates. This is deprecated, use context and context_id instead |
| `context` | string | Yes | The type of context this webhook is attached to. The value will be "PROJECT", "TEAM", or "FILE" |
| `context_id` | string | Yes | The ID of the context this webhook is attached to |
| `plan_api_id` | string | Yes | The plan API ID of the team or organization where this webhook was created |
| `status` | [WebhookV2Status](WebhookV2Status.md) | Yes |  |
| `client_id` | string,null | Yes | The client ID of the OAuth application that registered this webhook, if any |
| `passcode` | string | Yes | The passcode that will be passed back to the webhook endpoint. For security, when using the GET endpoints, the value is an empty string |
| `endpoint` | string | Yes | The endpoint that will be hit when the webhook is triggered |
| `description` | string,null | Yes | Optional user-provided description or name for the webhook. This is provided to help make maintaining a number of webhooks more convenient. Max length 140 characters. |

