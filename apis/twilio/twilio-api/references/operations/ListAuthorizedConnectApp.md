# GET /2010-04-01/Accounts/{AccountSid}/AuthorizedConnectApps.json

**Resource:** [Api20100401AuthorizedConnectApp](../resources/Api20100401AuthorizedConnectApp.md)
**Retrieve a list of authorized-connect-apps belonging to the account used to make the request**
**Operation ID:** `ListAuthorizedConnectApp`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the AuthorizedConnectApp resources to read. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
