# api.v2010.account.call.user_defined_message_subscription

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that subscribed to the User Defined Messages. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the User Defined Message Subscription is associated with. This refers to the Call SID that is producing the User Defined Messages. |
| `sid` | string | No | The SID that uniquely identifies this User Defined Message Subscription. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this User Defined Message Subscription was created, given in RFC 2822 format. |
| `uri` | string | No | The URI of the User Defined Message Subscription Resource, relative to `https://api.twilio.com`. |

