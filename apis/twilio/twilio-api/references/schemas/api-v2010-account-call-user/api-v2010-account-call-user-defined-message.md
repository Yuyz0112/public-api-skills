# api.v2010.account.call.user_defined_message

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created User Defined Message. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the User Defined Message is associated with. |
| `sid` | string | No | The SID that uniquely identifies this User Defined Message. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this User Defined Message was created, given in RFC 2822 format. |

