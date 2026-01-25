# api.v2010.account.available_phone_number_country

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country_code` | string (iso-country-code) | No | The [ISO-3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code of the country. |
| `country` | string | No | The name of the country. |
| `uri` | string (uri) | No | The URI of the Country resource, relative to `https://api.twilio.com`. |
| `beta` | boolean | No | Whether all phone numbers available in the country are new to the Twilio platform. `true` if they are and `false` if all numbers are not in the Twilio Phone Number Beta program. |
| `subresource_uris` | object (uri-map) | No | A list of related AvailablePhoneNumber resources identified by their URIs relative to `https://api.twilio.com`. |

