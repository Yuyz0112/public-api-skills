# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Siprec.json

**Resource:** [Api20100401Siprec](../resources/Api20100401Siprec.md)
**Create a Siprec**
**Operation ID:** `CreateSiprec`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Siprec resource. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Siprec resource is associated with. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.call.siprec](../schemas/api-v2010-account-call-siprec/api-v2010-account-call-siprec.md)

## Security

- **accountSid_authToken**
