# events

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-events.md) |
| GET | `/admin/api/2020-01/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/deprecated-202001-get-events-param-event-id.md) |
| GET | `/admin/api/2020-01/events/count.json` | Retrieves a count of events | [View](../operations/deprecated-202001-get-events-count.md) |
| GET | `/admin/api/2020-04/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-events.md) |
| GET | `/admin/api/2020-04/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/deprecated-202004-get-events-param-event-id.md) |
| GET | `/admin/api/2020-04/events/count.json` | Retrieves a count of events | [View](../operations/deprecated-202004-get-events-count.md) |
| GET | `/admin/api/2020-07/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-events.md) |
| GET | `/admin/api/2020-07/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/deprecated-202007-get-events-param-event-id.md) |
| GET | `/admin/api/2020-07/events/count.json` | Retrieves a count of events | [View](../operations/deprecated-202007-get-events-count.md) |
| GET | `/admin/api/2020-10/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-events.md) |
| GET | `/admin/api/2020-10/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/get-events-param-event-id.md) |
| GET | `/admin/api/2020-10/events/count.json` | Retrieves a count of events | [View](../operations/get-events-count.md) |
| GET | `/admin/api/2021-01/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-events.md) |
| GET | `/admin/api/2021-01/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/deprecated-202101-get-events-param-event-id.md) |
| GET | `/admin/api/2021-01/events/count.json` | Retrieves a count of events | [View](../operations/deprecated-202101-get-events-count.md) |
| GET | `/admin/api/unstable/events.json` | Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-events.md) |
| GET | `/admin/api/unstable/events/{event_id}.json` | Retrieves a single event by its ID | [View](../operations/deprecated-unstable-get-events-param-event-id.md) |
| GET | `/admin/api/unstable/events/count.json` | Retrieves a count of events | [View](../operations/deprecated-unstable-get-events-count.md) |
| GET | `/admin/api/2020-01/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-webhooks.md) |
| POST | `/admin/api/2020-01/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/deprecated-202001-create-webhooks.md) |
| GET | `/admin/api/2020-01/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/deprecated-202001-get-webhooks-count.md) |
| GET | `/admin/api/2020-01/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/deprecated-202001-get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/2020-01/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/deprecated-202001-update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/2020-01/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/deprecated-202001-delete-webhooks-param-webhook-id.md) |
| GET | `/admin/api/2020-04/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-webhooks.md) |
| POST | `/admin/api/2020-04/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/deprecated-202004-create-webhooks.md) |
| GET | `/admin/api/2020-04/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/deprecated-202004-get-webhooks-count.md) |
| GET | `/admin/api/2020-04/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/deprecated-202004-get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/2020-04/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/deprecated-202004-update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/2020-04/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/deprecated-202004-delete-webhooks-param-webhook-id.md) |
| GET | `/admin/api/2020-07/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-webhooks.md) |
| POST | `/admin/api/2020-07/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/deprecated-202007-create-webhooks.md) |
| GET | `/admin/api/2020-07/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/deprecated-202007-get-webhooks-count.md) |
| GET | `/admin/api/2020-07/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/deprecated-202007-get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/2020-07/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/deprecated-202007-update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/2020-07/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/deprecated-202007-delete-webhooks-param-webhook-id.md) |
| GET | `/admin/api/2020-10/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-webhooks.md) |
| POST | `/admin/api/2020-10/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/create-webhooks.md) |
| GET | `/admin/api/2020-10/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/get-webhooks-count.md) |
| GET | `/admin/api/2020-10/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/2020-10/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/2020-10/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/delete-webhooks-param-webhook-id.md) |
| GET | `/admin/api/2021-01/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-webhooks.md) |
| POST | `/admin/api/2021-01/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/deprecated-202101-create-webhooks.md) |
| GET | `/admin/api/2021-01/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/deprecated-202101-get-webhooks-count.md) |
| GET | `/admin/api/2021-01/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/deprecated-202101-get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/2021-01/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/deprecated-202101-update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/2021-01/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/deprecated-202101-delete-webhooks-param-webhook-id.md) |
| GET | `/admin/api/unstable/webhooks.json` | Retrieves a list of webhooks. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-webhooks.md) |
| POST | `/admin/api/unstable/webhooks.json` | Create a new webhook subscription by specifying both an address and a topic | [View](../operations/deprecated-unstable-create-webhooks.md) |
| GET | `/admin/api/unstable/webhooks/count.json` | Retrieves a count of existing webhook subscriptions | [View](../operations/deprecated-unstable-get-webhooks-count.md) |
| GET | `/admin/api/unstable/webhooks/{webhook_id}.json` | Retrieves a single webhook subscription | [View](../operations/deprecated-unstable-get-webhooks-param-webhook-id.md) |
| PUT | `/admin/api/unstable/webhooks/{webhook_id}.json` | Update a webhook subscription's topic or address URIs | [View](../operations/deprecated-unstable-update-webhooks-param-webhook-id.md) |
| DELETE | `/admin/api/unstable/webhooks/{webhook_id}.json` | Delete a webhook subscription | [View](../operations/deprecated-unstable-delete-webhooks-param-webhook-id.md) |
