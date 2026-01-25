# api.v2010.account.sip.sip_domain.sip_credential_list_mapping

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The unique id of the Account that is responsible for this resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this resource was created, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date that this resource was last updated, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `domain_sid` | string | No | The unique string that is created to identify the SipDomain resource. |
| `friendly_name` | string | No | A human readable descriptive text for this resource, up to 64 characters long. |
| `sid` | string | No | A 34 character string that uniquely identifies this resource. |
| `uri` | string | No | The URI for this resource, relative to `https://api.twilio.com` |

