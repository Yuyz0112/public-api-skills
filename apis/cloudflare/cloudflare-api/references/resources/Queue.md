# Queue

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/event_subscriptions/subscriptions` | List Event Subscriptions | [View](../operations/subscriptions-list.md) |
| POST | `/accounts/{account_id}/event_subscriptions/subscriptions` | Create Event Subscription | [View](../operations/subscriptions-create.md) |
| GET | `/accounts/{account_id}/event_subscriptions/subscriptions/{subscription_id}` | Get Event Subscription | [View](../operations/subscriptions-get.md) |
| DELETE | `/accounts/{account_id}/event_subscriptions/subscriptions/{subscription_id}` | Delete Event Subscription | [View](../operations/subscriptions-delete.md) |
| PATCH | `/accounts/{account_id}/event_subscriptions/subscriptions/{subscription_id}` | Update Event Subscription | [View](../operations/subscriptions-patch.md) |
| GET | `/accounts/{account_id}/queues` | List Queues | [View](../operations/queues-list.md) |
| POST | `/accounts/{account_id}/queues` | Create Queue | [View](../operations/queues-create.md) |
| GET | `/accounts/{account_id}/queues/{queue_id}` | Get Queue | [View](../operations/queues-get.md) |
| PUT | `/accounts/{account_id}/queues/{queue_id}` | Update Queue | [View](../operations/queues-update.md) |
| DELETE | `/accounts/{account_id}/queues/{queue_id}` | Delete Queue | [View](../operations/queues-delete.md) |
| PATCH | `/accounts/{account_id}/queues/{queue_id}` | Update Queue | [View](../operations/queues-update-partial.md) |
| GET | `/accounts/{account_id}/queues/{queue_id}/consumers` | List Queue Consumers | [View](../operations/queues-list-consumers.md) |
| POST | `/accounts/{account_id}/queues/{queue_id}/consumers` | Create a Queue Consumer | [View](../operations/queues-create-consumer.md) |
| GET | `/accounts/{account_id}/queues/{queue_id}/consumers/{consumer_id}` | Get Queue Consumer | [View](../operations/queues-get-consumer.md) |
| PUT | `/accounts/{account_id}/queues/{queue_id}/consumers/{consumer_id}` | Update Queue Consumer | [View](../operations/queues-update-consumer.md) |
| DELETE | `/accounts/{account_id}/queues/{queue_id}/consumers/{consumer_id}` | Delete Queue Consumer | [View](../operations/queues-delete-consumer.md) |
| POST | `/accounts/{account_id}/queues/{queue_id}/messages` | Push Message | [View](../operations/queues-push-message.md) |
| POST | `/accounts/{account_id}/queues/{queue_id}/messages/ack` | Acknowledge + Retry Queue Messages | [View](../operations/queues-ack-messages.md) |
| POST | `/accounts/{account_id}/queues/{queue_id}/messages/batch` | Push Message Batch | [View](../operations/queues-push-messages.md) |
| POST | `/accounts/{account_id}/queues/{queue_id}/messages/pull` | Pull Queue Messages | [View](../operations/queues-pull-messages.md) |
| GET | `/accounts/{account_id}/queues/{queue_id}/purge` | Get Queue Purge Status | [View](../operations/queues-purge-get.md) |
| POST | `/accounts/{account_id}/queues/{queue_id}/purge` | Purge Queue | [View](../operations/queues-purge.md) |
