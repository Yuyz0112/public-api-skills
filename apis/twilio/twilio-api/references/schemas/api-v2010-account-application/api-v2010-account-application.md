# api.v2010.account.application

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Application resource. |
| `api_version` | string | No | The API version used to start a new TwiML session. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `message_status_callback` | string (uri) | No | The URL we call using a POST method to send message status information to your application. |
| `sid` | string | No | The unique string that that we created to identify the Application resource. |
| `sms_fallback_method` | enum: GET, POST | No | The HTTP method we use to call `sms_fallback_url`. Can be: `GET` or `POST`. |
| `sms_fallback_url` | string (uri) | No | The URL that we call when an error occurs while retrieving or executing the TwiML from `sms_url`. |
| `sms_method` | enum: GET, POST | No | The HTTP method we use to call `sms_url`. Can be: `GET` or `POST`. |
| `sms_status_callback` | string (uri) | No | The URL we call using a POST method to send status information to your application about SMS messages that refer to the application. |
| `sms_url` | string (uri) | No | The URL we call when the phone number receives an incoming SMS message. |
| `status_callback` | string (uri) | No | The URL we call using the `status_callback_method` to send status information to your application. |
| `status_callback_method` | enum: GET, POST | No | The HTTP method we use to call `status_callback`. Can be: `GET` or `POST`. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `voice_caller_id_lookup` | boolean | No | Whether we look up the caller's caller-ID name from the CNAM database (additional charges apply). Can be: `true` or `false`. |
| `voice_fallback_method` | enum: GET, POST | No | The HTTP method we use to call `voice_fallback_url`. Can be: `GET` or `POST`. |
| `voice_fallback_url` | string (uri) | No | The URL that we call when an error occurs retrieving or executing the TwiML requested by `url`. |
| `voice_method` | enum: GET, POST | No | The HTTP method we use to call `voice_url`. Can be: `GET` or `POST`. |
| `voice_url` | string (uri) | No | The URL we call when the phone number assigned to this application receives a call. |
| `public_application_connect_enabled` | boolean | No | Whether to allow other Twilio accounts to dial this applicaton using Dial verb. Can be: `true` or `false`. |

