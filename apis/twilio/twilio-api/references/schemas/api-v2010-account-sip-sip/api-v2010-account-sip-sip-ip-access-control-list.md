# api.v2010.account.sip.sip_ip_access_control_list

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | A 34 character string that uniquely identifies this resource. |
| `account_sid` | string | No | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) that owns this resource. |
| `friendly_name` | string | No | A human readable descriptive text, up to 255 characters long. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this resource was created, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date that this resource was last updated, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `subresource_uris` | object (uri-map) | No | A list of the IpAddress resources associated with this IP access control list resource. |
| `uri` | string | No | The URI for this resource, relative to `https://api.twilio.com` |

