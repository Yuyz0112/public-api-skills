# GET /2010-04-01/Accounts/{AccountSid}/AuthorizedConnectApps/{ConnectAppSid}.json

**Resource:** [Api20100401AuthorizedConnectApp](../resources/Api20100401AuthorizedConnectApp.md)
**Fetch an instance of an authorized-connect-app**
**Operation ID:** `FetchAuthorizedConnectApp`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the AuthorizedConnectApp resource to fetch. |
| `ConnectAppSid` | path | string | Yes | The SID of the Connect App to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.authorized_connect_app](../schemas/api-v2010-account-authorized/api-v2010-account-authorized-connect-app.md)

## Security

- **accountSid_authToken**
