# api.v2010.account.sip.sip_credential_list.sip_credential

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | A 34 character string that uniquely identifies this resource. |
| `account_sid` | string | No | The unique id of the Account that is responsible for this resource. |
| `credential_list_sid` | string | No | The unique id that identifies the credential list that includes this credential. |
| `username` | string | No | The username for this credential. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this resource was created, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date that this resource was last updated, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `uri` | string | No | The URI for this resource, relative to `https://api.twilio.com` |

