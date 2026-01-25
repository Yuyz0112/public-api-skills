# DELETE /2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Recordings/{Sid}.json

**Resource:** [Api20100401ConferenceRecording](../resources/Api20100401ConferenceRecording.md)
**Delete a recording from your account**
**Operation ID:** `DeleteConferenceRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Conference Recording resources to delete. |
| `ConferenceSid` | path | string | Yes | The Conference SID that identifies the conference associated with the recording to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Conference Recording resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
