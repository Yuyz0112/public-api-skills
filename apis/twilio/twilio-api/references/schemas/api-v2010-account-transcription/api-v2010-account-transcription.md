# api.v2010.account.transcription

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Transcription resource. |
| `api_version` | string | No | The API version used to create the transcription. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `duration` | string | No | The duration of the transcribed audio in seconds. |
| `price` | number | No | The charge for the transcript in the currency associated with the account. This value is populated after the transcript is complete so it may not be available immediately. |
| `price_unit` | string (currency) | No | The currency in which `price` is measured, in [ISO 4127](https://www.iso.org/iso/home/standards/currency_codes.htm) format (e.g. `usd`, `eur`, `jpy`). |
| `recording_sid` | string | No | The SID of the [Recording](https://www.twilio.com/docs/voice/api/recording) from which the transcription was created. |
| `sid` | string | No | The unique string that that we created to identify the Transcription resource. |
| `status` | [transcription_enum_status](transcription-enum-status.md) | No |  |
| `transcription_text` | string | No | The text content of the transcription. |
| `type` | string | No | The transcription type. Can only be: `fast`. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

