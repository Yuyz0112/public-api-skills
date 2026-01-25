# event

Snapshot events allow you to track and react to activity in your Stripe integration. When
the state of another API resource changes, Stripe creates an `Event` object that contains
all the relevant information associated with that action, including the affected API
resource. For example, a successful payment triggers a `charge.succeeded` event, which
contains the `Charge` in the event's data property. Some actions trigger multiple events.
For example, if you create a new subscription for a customer, it triggers both a
`customer.subscription.created` event and a `charge.succeeded` event.

Configure an event destination in your account to listen for events that represent actions
your integration needs to respond to. Additionally, you can retrieve an individual event or
a list of events from the API.

[Connect](https://docs.stripe.com/connect) platforms can also receive event notifications
that occur in their connected accounts. These events include an account attribute that
identifies the relevant connected account.

You can access events through the [Retrieve Event API](https://docs.stripe.com/api/events#retrieve_event)
for 30 days.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | string | No | The connected account that originates the event. |
| `api_version` | string | No | The Stripe API version used to render `data` when the event was created. The contents of `data` never change, so this value remains static regardless of the API version currently in use. This property is populated only for events created on or after October 31, 2014. |
| `context` | string | No | Authentication context needed to fetch the event or related object. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `data` | [notification_event_data](notification-event-data.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: event | Yes | String representing the object's type. Objects of the same type share the same value. |
| `pending_webhooks` | integer | Yes | Number of webhooks that haven't been successfully delivered (for example, to return a 20x response) to the URLs you specify. |
| `request` | any | No | Information on the API request that triggers the event. |
| `type` | string | Yes | Description of the event (for example, `invoice.created` or `charge.refunded`). |

