# api.v2010.account.conference.conference_recording

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Conference Recording resource. |
| `api_version` | string | No | The API version used to create the recording. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Conference Recording resource is associated with. |
| `conference_sid` | string | No | The Conference SID that identifies the conference associated with the recording. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `start_time` | string (date-time-rfc-2822) | No | The start time of the recording in GMT and in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `duration` | string | No | The length of the recording in seconds. |
| `sid` | string | No | The unique string that that we created to identify the Conference Recording resource. |
| `price` | string | No | The one-time cost of creating the recording in the `price_unit` currency. |
| `price_unit` | string (currency) | No | The currency used in the `price` property. Example: `USD`. |
| `status` | [conference_recording_enum_status](conference-recording-enum-status.md) | No |  |
| `channels` | integer | No | The number of channels in the final recording file.  Can be: `1`, or `2`. Separating a two leg call into two separate channels of the recording file is supported in [Dial](https://www.twilio.com/docs/voice/twiml/dial#attributes-record) and [Outbound Rest API](https://www.twilio.com/docs/voice/make-calls) record options. |
| `source` | [conference_recording_enum_source](conference-recording-enum-source.md) | No |  |
| `error_code` | integer | No | The error code that describes why the recording is `absent`. The error code is described in our [Error Dictionary](https://www.twilio.com/docs/api/errors). This value is null if the recording `status` is not `absent`. |
| `encryption_details` | any | No | How to decrypt the recording if it was encrypted using [Call Recording Encryption](https://www.twilio.com/docs/voice/tutorials/voice-recording-encryption) feature. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

