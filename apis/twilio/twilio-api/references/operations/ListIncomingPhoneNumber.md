# GET /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers.json

**Resource:** [Api20100401IncomingPhoneNumber](../resources/Api20100401IncomingPhoneNumber.md)
**Retrieve a list of incoming-phone-numbers belonging to the account used to make the request.**
**Operation ID:** `ListIncomingPhoneNumber`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the IncomingPhoneNumber resources to read. |
| `Beta` | query | boolean | No | Whether to include phone numbers new to the Twilio platform. Can be: `true` or `false` and the default is `true`. |
| `FriendlyName` | query | string | No | A string that identifies the IncomingPhoneNumber resources to read. |
| `PhoneNumber` | query | string (phone-number) | No | The phone numbers of the IncomingPhoneNumber resources to read. You can specify partial numbers and use '*' as a wildcard for any digit. |
| `Origin` | query | string | No | Whether to include phone numbers based on their origin. Can be: `twilio` or `hosted`. By default, phone numbers of all origin are included. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
