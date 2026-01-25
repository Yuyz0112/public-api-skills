# api.v2010.account.recording.recording_add_on_result.recording_add_on_result_payload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The unique string that that we created to identify the Recording AddOnResult Payload resource. |
| `add_on_result_sid` | string | No | The SID of the AddOnResult to which the payload belongs. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult Payload resource. |
| `label` | string | No | The string provided by the vendor that describes the payload. |
| `add_on_sid` | string | No | The SID of the Add-on to which the result belongs. |
| `add_on_configuration_sid` | string | No | The SID of the Add-on configuration. |
| `content_type` | string | No | The MIME type of the payload. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `reference_sid` | string | No | The SID of the recording to which the AddOnResult resource that contains the payload belongs. |
| `subresource_uris` | object (uri-map) | No | A list of related resources identified by their relative URIs. |

