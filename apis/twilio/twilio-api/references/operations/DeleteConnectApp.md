# DELETE /2010-04-01/Accounts/{AccountSid}/ConnectApps/{Sid}.json

**Resource:** [Api20100401ConnectApp](../resources/Api20100401ConnectApp.md)
**Delete an instance of a connect-app**
**Operation ID:** `DeleteConnectApp`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the ConnectApp resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the ConnectApp resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
