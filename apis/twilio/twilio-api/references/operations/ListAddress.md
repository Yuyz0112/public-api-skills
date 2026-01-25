# GET /2010-04-01/Accounts/{AccountSid}/Addresses.json

**Resource:** [Api20100401Address](../resources/Api20100401Address.md)
**Operation ID:** `ListAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that is responsible for the Address resource to read. |
| `CustomerName` | query | string | No | The `customer_name` of the Address resources to read. |
| `FriendlyName` | query | string | No | The string that identifies the Address resources to read. |
| `EmergencyEnabled` | query | boolean | No | Whether the address can be associated to a number for emergency calling. |
| `IsoCountry` | query | string (iso-country-code) | No | The ISO country code of the Address resources to read. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
