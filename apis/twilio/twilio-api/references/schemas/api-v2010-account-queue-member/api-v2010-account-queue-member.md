# api.v2010.account.queue.member

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Member resource is associated with. |
| `date_enqueued` | string (date-time-rfc-2822) | No | The date that the member was enqueued, given in RFC 2822 format. |
| `position` | integer | No | This member's current position in the queue. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `wait_time` | integer | No | The number of seconds the member has been in the queue. |
| `queue_sid` | string | No | The SID of the Queue the member is in. |

