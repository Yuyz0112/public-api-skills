# ActivitySubscriptionCreateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_type` | enum: profile.update.bio, profile.update.profile_picture, profile.update.banner_picture... | Yes |  |
| `filter` | [ActivitySubscriptionFilter](ActivitySubscriptionFilter.md) | Yes |  |
| `tag` | string | No |  |
| `webhook_id` | [WebhookConfigId](WebhookConfigId.md) | No |  |

