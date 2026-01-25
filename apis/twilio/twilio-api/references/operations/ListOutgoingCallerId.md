# GET /2010-04-01/Accounts/{AccountSid}/OutgoingCallerIds.json

**Resource:** [Api20100401OutgoingCallerId](../resources/Api20100401OutgoingCallerId.md)
**Retrieve a list of outgoing-caller-ids belonging to the account used to make the request**
**Operation ID:** `ListOutgoingCallerId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the OutgoingCallerId resources to read. |
| `PhoneNumber` | query | string (phone-number) | No | The phone number of the OutgoingCallerId resources to read. |
| `FriendlyName` | query | string | No | The string that identifies the OutgoingCallerId resources to read. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
