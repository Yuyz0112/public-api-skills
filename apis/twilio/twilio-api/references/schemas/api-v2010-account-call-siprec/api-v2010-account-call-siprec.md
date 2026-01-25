# api.v2010.account.call.siprec

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The SID of the Siprec resource. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Siprec resource. |
| `call_sid` | string | No | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Siprec resource is associated with. |
| `name` | string | No | The user-specified name of this Siprec, if one was given when the Siprec was created. This may be used to stop the Siprec. |
| `status` | [siprec_enum_status](siprec-enum-status.md) | No |  |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

