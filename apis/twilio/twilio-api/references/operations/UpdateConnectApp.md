# POST /2010-04-01/Accounts/{AccountSid}/ConnectApps/{Sid}.json

**Resource:** [Api20100401ConnectApp](../resources/Api20100401ConnectApp.md)
**Update a connect-app with the specified parameters**
**Operation ID:** `UpdateConnectApp`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the ConnectApp resources to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the ConnectApp resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.connect_app](../schemas/api-v2010-account-connect/api-v2010-account-connect-app.md)

## Security

- **accountSid_authToken**
