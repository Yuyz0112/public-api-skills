# api.v2010.account.call.realtime_transcription

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The SID of the Transcription resource. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Transcription resource. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Transcription resource is associated with. |
| `name` | string | No | The user-specified name of this Transcription, if one was given when the Transcription was created. This may be used to stop the Transcription. |
| `status` | [realtime_transcription_enum_status](realtime-transcription-enum-status.md) | No |  |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `uri` | string | No |  |

