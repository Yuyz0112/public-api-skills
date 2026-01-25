# GET /2010-04-01/Accounts/{AccountSid}/Applications.json

**Resource:** [Api20100401Application](../resources/Api20100401Application.md)
**Retrieve a list of applications representing an application within the requesting account**
**Operation ID:** `ListApplication`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Application resources to read. |
| `FriendlyName` | query | string | No | The string that identifies the Application resources to read. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
