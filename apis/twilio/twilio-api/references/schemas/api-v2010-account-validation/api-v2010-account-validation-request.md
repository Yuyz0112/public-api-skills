# api.v2010.account.validation_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for the Caller ID. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Caller ID is associated with. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `phone_number` | string (phone-number) | No | The phone number to verify in [E.164](https://www.twilio.com/docs/glossary/what-e164) format, which consists of a + followed by the country code and subscriber number. |
| `validation_code` | string | No | The 6 digit validation code that someone must enter to validate the Caller ID  when `phone_number` is called. |

