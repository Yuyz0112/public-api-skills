# GET /2010-04-01/Accounts/{AccountSid}/Recordings/{RecordingSid}/Transcriptions/{Sid}.json

**Resource:** [Api20100401RecordingTranscription](../resources/Api20100401RecordingTranscription.md)
**Operation ID:** `FetchRecordingTranscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Transcription resource to fetch. |
| `RecordingSid` | path | string | Yes | The SID of the [Recording](https://www.twilio.com/docs/voice/api/recording) that created the transcription to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Transcription resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.recording.recording_transcription](../schemas/api-v2010-account-recording-recording/api-v2010-account-recording-recording-transcription.md)

## Security

- **accountSid_authToken**
