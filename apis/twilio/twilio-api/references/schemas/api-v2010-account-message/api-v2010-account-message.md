# api.v2010.account.message

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | string | No | The text content of the message |
| `num_segments` | string | No | The number of segments that make up the complete message. SMS message bodies that exceed the [character limit](https://www.twilio.com/docs/glossary/what-sms-character-limit) are segmented and charged as multiple messages. Note: For messages sent via a Messaging Service, `num_segments` is initially `0`, since a sender hasn't yet been assigned. |
| `direction` | [message_enum_direction](message-enum-direction.md) | No |  |
| `from` | string (phone-number) | No | The sender's phone number (in [E.164](https://en.wikipedia.org/wiki/E.164) format), [alphanumeric sender ID](https://www.twilio.com/docs/sms/quickstart), [Wireless SIM](https://www.twilio.com/docs/iot/wireless/programmable-wireless-send-machine-machine-sms-commands), [short code](https://www.twilio.com/en-us/messaging/channels/sms/short-codes), or  [channel address](https://www.twilio.com/docs/messaging/channels) (e.g., `whatsapp:+15554449999`). For incoming messages, this is the number or channel address of the sender. For outgoing messages, this value is a Twilio phone number, alphanumeric sender ID, short code, or channel address from which the message is sent. |
| `to` | string | No | The recipient's phone number (in [E.164](https://en.wikipedia.org/wiki/E.164) format) or [channel address](https://www.twilio.com/docs/messaging/channels) (e.g. `whatsapp:+15552229999`) |
| `date_updated` | string (date-time-rfc-2822) | No | The [RFC 2822](https://datatracker.ietf.org/doc/html/rfc2822#section-3.3) timestamp (in GMT) of when the Message resource was last updated |
| `price` | string | No | The amount billed for the message in the currency specified by `price_unit`. The `price` is populated after the message has been sent/received, and may not be immediately availalble. View the [Pricing page](https://www.twilio.com/en-us/pricing) for more details. |
| `error_message` | string | No | The description of the `error_code` if the Message `status` is `failed` or `undelivered`. If no error was encountered, the value is `null`. The value returned in this field for a specific error cause is subject to change as Twilio improves errors. Users should not use the `error_code` and `error_message` fields programmatically. |
| `uri` | string | No | The URI of the Message resource, relative to `https://api.twilio.com`. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with the Message resource |
| `num_media` | string | No | The number of media files associated with the Message resource. |
| `status` | [message_enum_status](message-enum-status.md) | No |  |
| `messaging_service_sid` | string | No | The SID of the [Messaging Service](https://www.twilio.com/docs/messaging/api/service-resource) associated with the Message resource. A unique default value is assigned if a Messaging Service is not used. |
| `sid` | string | No | The unique, Twilio-provided string that identifies the Message resource. |
| `date_sent` | string (date-time-rfc-2822) | No | The [RFC 2822](https://datatracker.ietf.org/doc/html/rfc2822#section-3.3) timestamp (in GMT) of when the Message was sent. For an outgoing message, this is when Twilio sent the message. For an incoming message, this is when Twilio sent the HTTP request to your incoming message webhook URL. |
| `date_created` | string (date-time-rfc-2822) | No | The [RFC 2822](https://datatracker.ietf.org/doc/html/rfc2822#section-3.3) timestamp (in GMT) of when the Message resource was created |
| `error_code` | integer | No | The [error code](https://www.twilio.com/docs/api/errors) returned if the Message `status` is `failed` or `undelivered`. If no error was encountered, the value is `null`. The value returned in this field for a specific error cause is subject to change as Twilio improves errors. Users should not use the `error_code` and `error_message` fields programmatically. |
| `price_unit` | string (currency) | No | The currency in which `price` is measured, in [ISO 4127](https://www.iso.org/iso/home/standards/currency_codes.htm) format (e.g. `usd`, `eur`, `jpy`). |
| `api_version` | string | No | The API version used to process the Message |
| `subresource_uris` | object (uri-map) | No | A list of related resources identified by their URIs relative to `https://api.twilio.com` |

