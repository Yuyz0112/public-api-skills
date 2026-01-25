# DELETE /2010-04-01/Accounts/{AccountSid}/Transcriptions/{Sid}.json

**Resource:** [Api20100401Transcription](../resources/Api20100401Transcription.md)
**Delete a transcription from the account used to make the request**
**Operation ID:** `DeleteTranscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Transcription resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Transcription resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
