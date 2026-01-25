# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Transcriptions.json

**Resource:** [Api20100401CallTranscription](../resources/Api20100401CallTranscription.md)
**Create a Transcription**
**Operation ID:** `CreateRealtimeTranscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Transcription resource. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Transcription resource is associated with. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.call.realtime_transcription](../schemas/api-v2010-account-call-realtime/api-v2010-account-call-realtime-transcription.md)

## Security

- **accountSid_authToken**
