# GET /2010-04-01/Accounts/{AccountSid}/AvailablePhoneNumbers/{CountryCode}/Mobile.json

**Resource:** [Api20100401Mobile](../resources/Api20100401Mobile.md)
**Operation ID:** `ListAvailablePhoneNumberMobile`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) requesting the AvailablePhoneNumber resources. |
| `CountryCode` | path | string (iso-country-code) | Yes | The [ISO-3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code of the country from which to read phone numbers. |
| `AreaCode` | query | integer | No | The area code of the phone numbers to read. Applies to only phone numbers in the US and Canada. |
| `Contains` | query | string | No | Matching pattern to identify phone numbers. This pattern can be between 2 and 16 characters long and allows all digits (0-9) and all non-diacritic latin alphabet letters (a-z, A-Z). It accepts four meta-characters: `*`, `%`, `+`, `$`. The `*` and `%` meta-characters can appear multiple times in the pattern. To match wildcards at the beginning or end of the pattern, use `*` to match any single character or `%` to match a sequence of characters. If you use the wildcard patterns, it must include at least two non-meta-characters, and wildcards cannot be used between non-meta-characters. To match the beginning of a pattern, start the pattern with `+`. To match the end of the pattern, append the pattern with `$`. These meta-characters can't be adjacent to each other. |
| `SmsEnabled` | query | boolean | No | Whether the phone numbers can receive text messages. Can be: `true` or `false`. |
| `MmsEnabled` | query | boolean | No | Whether the phone numbers can receive MMS messages. Can be: `true` or `false`. |
| `VoiceEnabled` | query | boolean | No | Whether the phone numbers can receive calls. Can be: `true` or `false`. |
| `ExcludeAllAddressRequired` | query | boolean | No | Whether to exclude phone numbers that require an [Address](https://www.twilio.com/docs/usage/api/address). Can be: `true` or `false` and the default is `false`. |
| `ExcludeLocalAddressRequired` | query | boolean | No | Whether to exclude phone numbers that require a local [Address](https://www.twilio.com/docs/usage/api/address). Can be: `true` or `false` and the default is `false`. |
| `ExcludeForeignAddressRequired` | query | boolean | No | Whether to exclude phone numbers that require a foreign [Address](https://www.twilio.com/docs/usage/api/address). Can be: `true` or `false` and the default is `false`. |
| `Beta` | query | boolean | No | Whether to read phone numbers that are new to the Twilio platform. Can be: `true` or `false` and the default is `true`. |
| `NearNumber` | query | string (phone-number) | No | Given a phone number, find a geographically close number within `distance` miles. Distance defaults to 25 miles. Applies to only phone numbers in the US and Canada. |
| `NearLatLong` | query | string | No | Given a latitude/longitude pair `lat,long` find geographically close numbers within `distance` miles. Applies to only phone numbers in the US and Canada. |
| `Distance` | query | integer | No | The search radius, in miles, for a `near_` query.  Can be up to `500` and the default is `25`. Applies to only phone numbers in the US and Canada. |
| `InPostalCode` | query | string | No | Limit results to a particular postal code. Given a phone number, search within the same postal code as that number. Applies to only phone numbers in the US and Canada. |
| `InRegion` | query | string | No | Limit results to a particular region, state, or province. Given a phone number, search within the same region as that number. Applies to only phone numbers in the US and Canada. |
| `InRateCenter` | query | string | No | Limit results to a specific rate center, or given a phone number search within the same rate center as that number. Requires `in_lata` to be set as well. Applies to only phone numbers in the US and Canada. |
| `InLata` | query | string | No | Limit results to a specific local access and transport area ([LATA](https://en.wikipedia.org/wiki/Local_access_and_transport_area)). Given a phone number, search within the same [LATA](https://en.wikipedia.org/wiki/Local_access_and_transport_area) as that number. Applies to only phone numbers in the US and Canada. |
| `InLocality` | query | string | No | Limit results to a particular locality or city. Given a phone number, search within the same Locality as that number. |
| `FaxEnabled` | query | boolean | No | Whether the phone numbers can receive faxes. Can be: `true` or `false`. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
