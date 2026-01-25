# GET /2010-04-01/Accounts/{AccountSid}/AvailablePhoneNumbers/{CountryCode}.json

**Resource:** [Api20100401AvailablePhoneNumberCountry](../resources/Api20100401AvailablePhoneNumberCountry.md)
**Operation ID:** `FetchAvailablePhoneNumberCountry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) requesting the available phone number Country resource. |
| `CountryCode` | path | string (iso-country-code) | Yes | The [ISO-3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code of the country to fetch available phone number information about. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.available_phone_number_country](../schemas/api-v2010-account-available/api-v2010-account-available-phone-number-country.md)

## Security

- **accountSid_authToken**
