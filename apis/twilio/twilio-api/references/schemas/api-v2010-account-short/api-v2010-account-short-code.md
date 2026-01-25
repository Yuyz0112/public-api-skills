# api.v2010.account.short_code

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this ShortCode resource. |
| `api_version` | string | No | The API version used to start a new TwiML session when an SMS message is sent to this short code. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `friendly_name` | string | No | A string that you assigned to describe this resource. By default, the `FriendlyName` is the short code. |
| `short_code` | string | No | The short code. e.g., 894546. |
| `sid` | string | No | The unique string that that we created to identify this ShortCode resource. |
| `sms_fallback_method` | enum: GET, POST | No | The HTTP method we use to call the `sms_fallback_url`. Can be: `GET` or `POST`. |
| `sms_fallback_url` | string (uri) | No | The URL that we call if an error occurs while retrieving or executing the TwiML from `sms_url`. |
| `sms_method` | enum: GET, POST | No | The HTTP method we use to call the `sms_url`. Can be: `GET` or `POST`. |
| `sms_url` | string (uri) | No | The URL we call when receiving an incoming SMS message to this short code. |
| `uri` | string | No | The URI of this resource, relative to `https://api.twilio.com`. |

