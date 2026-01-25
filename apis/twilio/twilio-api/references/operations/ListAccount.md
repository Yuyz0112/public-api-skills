# GET /2010-04-01/Accounts.json

**Resource:** [Api20100401Account](../resources/Api20100401Account.md)
**Retrieves a collection of Accounts belonging to the account used to make the request**
**Operation ID:** `ListAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `FriendlyName` | query | string | No | Only return the Account resources with friendly names that exactly match this name. |
| `Status` | query | account_enum_status | No | Only return Account resources with the given status. Can be `closed`, `suspended` or `active`. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
