# api.v2010.account.call.stream

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The SID of the Stream resource. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Stream resource. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Stream resource is associated with. |
| `name` | string | No | The user-specified name of this Stream, if one was given when the Stream was created. This can be used to stop the Stream. |
| `status` | [stream_enum_status](stream-enum-status.md) | No |  |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

