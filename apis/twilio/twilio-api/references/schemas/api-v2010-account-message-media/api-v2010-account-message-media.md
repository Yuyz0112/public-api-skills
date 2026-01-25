# api.v2010.account.message.media

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with this Media resource. |
| `content_type` | string | No | The default [MIME type](https://en.wikipedia.org/wiki/Internet_media_type) of the media, for example `image/jpeg`, `image/png`, or `image/gif`. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT when this Media resource was created, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT when this Media resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `parent_sid` | string | No | The SID of the Message resource that is associated with this Media resource. |
| `sid` | string | No | The unique string that identifies this Media resource. |
| `uri` | string | No | The URI of this Media resource, relative to `https://api.twilio.com`. |

