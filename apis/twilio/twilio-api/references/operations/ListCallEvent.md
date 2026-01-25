# GET /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Events.json

**Resource:** [Api20100401Event](../resources/Api20100401Event.md)
**Retrieve a list of all events for a call.**
**Operation ID:** `ListCallEvent`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique SID identifier of the Account. |
| `CallSid` | path | string | Yes | The unique SID identifier of the Call. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
