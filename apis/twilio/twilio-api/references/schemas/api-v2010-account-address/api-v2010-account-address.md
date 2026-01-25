# api.v2010.account.address

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that is responsible for the Address resource. |
| `city` | string | No | The city in which the address is located. |
| `customer_name` | string | No | The name associated with the address.This property has a maximum length of 16 4-byte characters, or 21 3-byte characters. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `iso_country` | string (iso-country-code) | No | The ISO country code of the address. |
| `postal_code` | string | No | The postal code of the address. |
| `region` | string | No | The state or region of the address. |
| `sid` | string | No | The unique string that that we created to identify the Address resource. |
| `street` | string | No | The number and street address of the address. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `emergency_enabled` | boolean | No | Whether emergency calling has been enabled on this number. |
| `validated` | boolean | No | Whether the address has been validated to comply with local regulation. In countries that require valid addresses, an invalid address will not be accepted. `true` indicates the Address has been validated. `false` indicate the country doesn't require validation or the Address is not valid. |
| `verified` | boolean | No | Whether the address has been verified to comply with regulation. In countries that require valid addresses, an invalid address will not be accepted. `true` indicates the Address has been verified. `false` indicate the country doesn't require verified or the Address is not valid. |
| `street_secondary` | string | No | The additional number and street address of the address. |

