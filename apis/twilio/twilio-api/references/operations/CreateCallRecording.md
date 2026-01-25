# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings.json

**Resource:** [Api20100401CallRecording](../resources/Api20100401CallRecording.md)
**Create a recording for the call**
**Operation ID:** `CreateCallRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) to associate the resource with. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.call.call_recording](../schemas/api-v2010-account-call-call/api-v2010-account-call-call-recording.md)

## Security

- **accountSid_authToken**
