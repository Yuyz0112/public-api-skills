# GET /2010-04-01/Accounts/{AccountSid}/Transcriptions/{Sid}.json

**Resource:** [Api20100401Transcription](../resources/Api20100401Transcription.md)
**Fetch an instance of a Transcription**
**Operation ID:** `FetchTranscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Transcription resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Transcription resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.transcription](../schemas/api-v2010-account-transcription/api-v2010-account-transcription.md)

## Security

- **accountSid_authToken**
