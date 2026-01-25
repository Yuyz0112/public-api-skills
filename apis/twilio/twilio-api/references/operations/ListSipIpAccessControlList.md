# GET /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists.json

**Resource:** [Api20100401IpAccessControlList](../resources/Api20100401IpAccessControlList.md)
**Retrieve a list of IpAccessControlLists that belong to the account used to make the request**
**Operation ID:** `ListSipIpAccessControlList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
