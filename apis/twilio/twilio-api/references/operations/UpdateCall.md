# POST /2010-04-01/Accounts/{AccountSid}/Calls/{Sid}.json

**Resource:** [Api20100401Call](../resources/Api20100401Call.md)
**Initiates a call redirect or terminates a call**
**Operation ID:** `UpdateCall`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Call resource(s) to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Call resource to update |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.call](../schemas/api-v2010-account-call/api-v2010-account-call.md)

## Security

- **accountSid_authToken**
