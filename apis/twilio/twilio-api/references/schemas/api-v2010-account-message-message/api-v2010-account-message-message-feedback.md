# api.v2010.account.message.message_feedback

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with this MessageFeedback resource. |
| `message_sid` | string | No | The SID of the Message resource associated with this MessageFeedback resource. |
| `outcome` | [message_feedback_enum_outcome](message-feedback-enum-outcome.md) | No |  |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT when this MessageFeedback resource was created, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT when this MessageFeedback resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

