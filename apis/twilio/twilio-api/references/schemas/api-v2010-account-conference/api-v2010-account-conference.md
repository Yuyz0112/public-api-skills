# api.v2010.account.conference

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Conference resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in UTC that this resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in UTC that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `api_version` | string | No | The API version used to create this conference. |
| `friendly_name` | string | No | A string that you assigned to describe this conference room. Maximum length is 128 characters. |
| `region` | string | No | A string that represents the Twilio Region where the conference audio was mixed. May be `us1`, `us2`, `ie1`,  `de1`, `sg1`, `br1`, `au1`, and `jp1`. Basic conference audio will always be mixed in `us1`. Global Conference audio will be mixed nearest to the majority of participants. |
| `sid` | string | No | The unique, Twilio-provided string used to identify this Conference resource. |
| `status` | [conference_enum_status](conference-enum-status.md) | No |  |
| `uri` | string | No | The URI of this resource, relative to `https://api.twilio.com`. |
| `subresource_uris` | object (uri-map) | No | A list of related resources identified by their URIs relative to `https://api.twilio.com`. |
| `reason_conference_ended` | [conference_enum_reason_conference_ended](conference-enum-reason-conference-ended.md) | No |  |
| `call_sid_ending_conference` | string | No | The call SID that caused the conference to end. |

