# api.v2010.account.usage.usage_trigger

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that the trigger monitors. |
| `api_version` | string | No | The API version used to create the resource. |
| `callback_method` | enum: GET, POST | No | The HTTP method we use to call `callback_url`. Can be: `GET` or `POST`. |
| `callback_url` | string (uri) | No | The URL we call using the `callback_method` when the trigger fires. |
| `current_value` | string | No | The current value of the field the trigger is watching. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_fired` | string (date-time-rfc-2822) | No | The date and time in GMT that the trigger was last fired specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `friendly_name` | string | No | The string that you assigned to describe the trigger. |
| `recurring` | [usage_trigger_enum_recurring](usage-trigger-enum-recurring.md) | No |  |
| `sid` | string | No | The unique string that that we created to identify the UsageTrigger resource. |
| `trigger_by` | [usage_trigger_enum_trigger_field](usage-trigger-enum-trigger-field.md) | No |  |
| `trigger_value` | string | No | The value at which the trigger will fire.  Must be a positive, numeric value. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `usage_category` | string | No | The usage category the trigger watches. Must be one of the supported [usage categories](https://www.twilio.com/docs/usage/api/usage-record#usage-categories). |
| `usage_record_uri` | string | No | The URI of the [UsageRecord](https://www.twilio.com/docs/usage/api/usage-record) resource this trigger watches, relative to `https://api.twilio.com`. |

