# api.v2010.account.available_phone_number_country.available_phone_number_toll_free

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `friendly_name` | string (phone-number) | No | A formatted version of the phone number. |
| `phone_number` | string (phone-number) | No | The phone number in [E.164](https://www.twilio.com/docs/glossary/what-e164) format, which consists of a + followed by the country code and subscriber number. |
| `lata` | string | No | The [LATA](https://en.wikipedia.org/wiki/Local_access_and_transport_area) of this phone number. Available for only phone numbers from the US and Canada. |
| `locality` | string | No | The locality or city of this phone number's location. |
| `rate_center` | string | No | The [rate center](https://en.wikipedia.org/wiki/Telephone_exchange) of this phone number. Available for only phone numbers from the US and Canada. |
| `latitude` | number | No | The latitude of this phone number's location. Available for only phone numbers from the US and Canada. |
| `longitude` | number | No | The longitude of this phone number's location. Available for only phone numbers from the US and Canada. |
| `region` | string | No | The two-letter state or province abbreviation of this phone number's location. Available for only phone numbers from the US and Canada. |
| `postal_code` | string | No | The postal or ZIP code of this phone number's location. Available for only phone numbers from the US and Canada. |
| `iso_country` | string (iso-country-code) | No | The [ISO country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) of this phone number. |
| `address_requirements` | string | No | The type of [Address](https://www.twilio.com/docs/usage/api/address) resource the phone number requires. Can be: `none`, `any`, `local`, or `foreign`. `none` means no address is required. `any` means an address is required, but it can be anywhere in the world. `local` means an address in the phone number's country is required. `foreign` means an address outside of the phone number's country is required. |
| `beta` | boolean | No | Whether the phone number is new to the Twilio platform. Can be: `true` or `false`. |
| `capabilities` | object (phone-number-capabilities) | No | The set of Boolean properties that indicate whether a phone number can receive calls or messages.  Capabilities are: `Voice`, `SMS`, and `MMS` and each capability can be: `true` or `false`. |

## Nested Fields

### `capabilities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mms` | boolean | No |  |
| `sms` | boolean | No |  |
| `voice` | boolean | No |  |
| `fax` | boolean | No |  |

