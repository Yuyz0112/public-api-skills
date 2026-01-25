# Account Activity

Endpoints relating to retrieving, managing AAA subscriptions

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/2/account_activity/replay/webhooks/{webhook_id}/subscriptions/all` | Create replay job | [View](../operations/createAccountActivityReplayJob.md) |
| GET | `/2/account_activity/subscriptions/count` | Get subscription count | [View](../operations/getAccountActivitySubscriptionCount.md) |
| GET | `/2/account_activity/webhooks/{webhook_id}/subscriptions/all` | Validate subscription | [View](../operations/validateAccountActivitySubscription.md) |
| POST | `/2/account_activity/webhooks/{webhook_id}/subscriptions/all` | Create subscription | [View](../operations/createAccountActivitySubscription.md) |
| GET | `/2/account_activity/webhooks/{webhook_id}/subscriptions/all/list` | Get subscriptions | [View](../operations/getAccountActivitySubscriptions.md) |
| DELETE | `/2/account_activity/webhooks/{webhook_id}/subscriptions/{user_id}/all` | Delete subscription | [View](../operations/deleteAccountActivitySubscription.md) |
