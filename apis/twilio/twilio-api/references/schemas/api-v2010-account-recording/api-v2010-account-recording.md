# api.v2010.account.recording

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording resource. |
| `api_version` | string | No | The API version used during the recording. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Recording resource is associated with. This will always refer to the parent leg of a two-leg call. |
| `conference_sid` | string | No | The Conference SID that identifies the conference associated with the recording, if a conference recording. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `start_time` | string (date-time-rfc-2822) | No | The start time of the recording in GMT and in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `duration` | string | No | The length of the recording in seconds. |
| `sid` | string | No | The unique string that that we created to identify the Recording resource. |
| `price` | string | No | The one-time cost of creating the recording in the `price_unit` currency. |
| `price_unit` | string | No | The currency used in the `price` property. Example: `USD`. |
| `status` | [recording_enum_status](recording-enum-status.md) | No |  |
| `channels` | integer | No | The number of channels in the recording resource. For information on specifying the number of channels in the downloaded recording file, check out [Fetch a Recording’s media file](https://www.twilio.com/docs/voice/api/recording#download-dual-channel-media-file). |
| `source` | [recording_enum_source](recording-enum-source.md) | No |  |
| `error_code` | integer | No | The error code that describes why the recording is `absent`. The error code is described in our [Error Dictionary](https://www.twilio.com/docs/api/errors). This value is null if the recording `status` is not `absent`. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `encryption_details` | any | No | How to decrypt the recording if it was encrypted using [Call Recording Encryption](https://www.twilio.com/docs/voice/tutorials/voice-recording-encryption) feature. |
| `subresource_uris` | object (uri-map) | No | A list of related resources identified by their relative URIs. |
| `media_url` | string (uri) | No | The URL of the media file associated with this recording resource. When stored externally, this is the full URL location of the media file. |

