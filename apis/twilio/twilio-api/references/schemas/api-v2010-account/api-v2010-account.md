# api.v2010.account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_token` | string | No | The authorization token for this account. This token should be kept a secret, so no sharing. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this account was created, in GMT in RFC 2822 format |
| `date_updated` | string (date-time-rfc-2822) | No | The date that this account was last updated, in GMT in RFC 2822 format. |
| `friendly_name` | string | No | A human readable description of this account, up to 64 characters long. By default the FriendlyName is your email address. |
| `owner_account_sid` | string | No | The unique 34 character id that represents the parent of this account. The OwnerAccountSid of a parent account is it's own sid. |
| `sid` | string | No | A 34 character string that uniquely identifies this resource. |
| `status` | [account_enum_status](account-enum-status.md) | No |  |
| `subresource_uris` | object (uri-map) | No | A Map of various subresources available for the given Account Instance |
| `type` | [account_enum_type](account-enum-type.md) | No |  |
| `uri` | string | No | The URI for this resource, relative to `https://api.twilio.com` |

