# POST /2010-04-01/Accounts/{AccountSid}/Calls.json

**Resource:** [Api20100401Call](../resources/Api20100401Call.md)
**Create a new outgoing call to phones, SIP-enabled endpoints or Twilio Client connections**
**Operation ID:** `CreateCall`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.call](../schemas/api-v2010-account-call/api-v2010-account-call.md)

## Security

- **accountSid_authToken**
