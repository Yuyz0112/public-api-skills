# DELETE /2010-04-01/Accounts/{AccountSid}/Recordings/{RecordingSid}/Transcriptions/{Sid}.json

**Resource:** [Api20100401RecordingTranscription](../resources/Api20100401RecordingTranscription.md)
**Operation ID:** `DeleteRecordingTranscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Transcription resources to delete. |
| `RecordingSid` | path | string | Yes | The SID of the [Recording](https://www.twilio.com/docs/voice/api/recording) that created the transcription to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Transcription resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
