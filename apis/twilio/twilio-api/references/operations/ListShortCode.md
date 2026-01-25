# GET /2010-04-01/Accounts/{AccountSid}/SMS/ShortCodes.json

**Resource:** [Api20100401ShortCode](../resources/Api20100401ShortCode.md)
**Retrieve a list of short-codes belonging to the account used to make the request**
**Operation ID:** `ListShortCode`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the ShortCode resource(s) to read. |
| `FriendlyName` | query | string | No | The string that identifies the ShortCode resources to read. |
| `ShortCode` | query | string | No | Only show the ShortCode resources that match this pattern. You can specify partial numbers and use '*' as a wildcard for any digit. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
