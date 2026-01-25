# api.v2010.account.sip.sip_ip_access_control_list.sip_ip_address

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | A 34 character string that uniquely identifies this resource. |
| `account_sid` | string | No | The unique id of the Account that is responsible for this resource. |
| `friendly_name` | string | No | A human readable descriptive text for this resource, up to 255 characters long. |
| `ip_address` | string | No | An IP address in dotted decimal notation from which you want to accept traffic. Any SIP requests from this IP address will be allowed by Twilio. IPv4 only supported today. |
| `cidr_prefix_length` | integer | No | An integer representing the length of the CIDR prefix to use with this IP address when accepting traffic. By default the entire IP address is used. |
| `ip_access_control_list_sid` | string | No | The unique id of the IpAccessControlList resource that includes this resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date that this resource was created, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date that this resource was last updated, given as GMT in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. |
| `uri` | string | No | The URI for this resource, relative to `https://api.twilio.com` |

