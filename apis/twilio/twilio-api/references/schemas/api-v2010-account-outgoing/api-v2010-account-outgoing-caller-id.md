# api.v2010.account.outgoing_caller_id

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The unique string that that we created to identify the OutgoingCallerId resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the OutgoingCallerId resource. |
| `phone_number` | string (phone-number) | No | The phone number in [E.164](https://www.twilio.com/docs/glossary/what-e164) format, which consists of a + followed by the country code and subscriber number. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

