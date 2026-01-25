# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Siprec/{Sid}.json

**Resource:** [Api20100401Siprec](../resources/Api20100401Siprec.md)
**Stop a Siprec using either the SID of the Siprec resource or the `name` used when creating the resource**
**Operation ID:** `UpdateSiprec`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Siprec resource. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Siprec resource is associated with. |
| `Sid` | path | string | Yes | The SID of the Siprec resource, or the `name` used when creating the resource |

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
