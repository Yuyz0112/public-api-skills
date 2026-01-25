# api.v2010.account.incoming_phone_number.incoming_phone_number_toll_free

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resource. |
| `address_sid` | string | No | The SID of the Address resource associated with the phone number. |
| `address_requirements` | [incoming_phone_number_toll_free_enum_address_requirement](incoming-phone-number-toll-free-enum-address-requirement.md) | No |  |
| `api_version` | string | No | The API version used to start a new TwiML session. |
| `beta` | boolean | No | Whether the phone number is new to the Twilio platform. Can be: `true` or `false`. |
| `capabilities` | object (phone-number-capabilities) | No | The set of Boolean properties that indicate whether a phone number can receive calls or messages.  Capabilities are  `Voice`, `SMS`, and `MMS` and each capability can be: `true` or `false`. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `identity_sid` | string | No | The SID of the Identity resource that we associate with the phone number. Some regions require an Identity to meet local regulations. |
| `phone_number` | string (phone-number) | No | The phone number in [E.164](https://www.twilio.com/docs/glossary/what-e164) format, which consists of a + followed by the country code and subscriber number. |
| `origin` | string | No | The phone number's origin. `twilio` identifies Twilio-owned phone numbers and `hosted` identifies hosted phone numbers. |
| `sid` | string | No | The unique string that that we created to identify the resource. |
| `sms_application_sid` | string | No | The SID of the application that handles SMS messages sent to the phone number. If an `sms_application_sid` is present, we ignore all `sms_*_url` values and use those of the application. |
| `sms_fallback_method` | enum: GET, POST | No | The HTTP method we use to call `sms_fallback_url`. Can be: `GET` or `POST`. |
| `sms_fallback_url` | string (uri) | No | The URL that we call when an error occurs while retrieving or executing the TwiML from `sms_url`. |
| `sms_method` | enum: GET, POST | No | The HTTP method we use to call `sms_url`. Can be: `GET` or `POST`. |
| `sms_url` | string (uri) | No | The URL we call when the phone number receives an incoming SMS message. |
| `status_callback` | string (uri) | No | The URL we call using the `status_callback_method` to send status information to your application. |
| `status_callback_method` | enum: GET, POST | No | The HTTP method we use to call `status_callback`. Can be: `GET` or `POST`. |
| `trunk_sid` | string | No | The SID of the Trunk that handles calls to the phone number. If a `trunk_sid` is present, we ignore all of the voice urls and voice applications and use those set on the Trunk. Setting a `trunk_sid` will automatically delete your `voice_application_sid` and vice versa. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `voice_receive_mode` | [incoming_phone_number_toll_free_enum_voice_receive_mode](incoming-phone-number-toll-free-enum-voice-receive-mode.md) | No |  |
| `voice_application_sid` | string | No | The SID of the application that handles calls to the phone number. If a `voice_application_sid` is present, we ignore all of the voice urls and use those set on the application. Setting a `voice_application_sid` will automatically delete your `trunk_sid` and vice versa. |
| `voice_caller_id_lookup` | boolean | No | Whether we look up the caller's caller-ID name from the CNAM database ($0.01 per look up). Can be: `true` or `false`. |
| `voice_fallback_method` | enum: GET, POST | No | The HTTP method we use to call `voice_fallback_url`. Can be: `GET` or `POST`. |
| `voice_fallback_url` | string (uri) | No | The URL that we call when an error occurs retrieving or executing the TwiML requested by `url`. |
| `voice_method` | enum: GET, POST | No | The HTTP method we use to call `voice_url`. Can be: `GET` or `POST`. |
| `voice_url` | string (uri) | No | The URL we call when the phone number receives a call. The `voice_url` will not be used if a `voice_application_sid` or a `trunk_sid` is set. |
| `emergency_status` | [incoming_phone_number_toll_free_enum_emergency_status](incoming-phone-number-toll-free-enum-emergency-status.md) | No |  |
| `emergency_address_sid` | string | No | The SID of the emergency address configuration that we use for emergency calling from this phone number. |
| `emergency_address_status` | [incoming_phone_number_toll_free_enum_emergency_address_status](incoming-phone-number-toll-free-enum-emergency-address-status.md) | No |  |
| `bundle_sid` | string | No | The SID of the Bundle resource that you associate with the phone number. Some regions require a Bundle to meet local Regulations. |
| `status` | string | No |  |

## Nested Fields

### `capabilities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mms` | boolean | No |  |
| `sms` | boolean | No |  |
| `voice` | boolean | No |  |
| `fax` | boolean | No |  |

