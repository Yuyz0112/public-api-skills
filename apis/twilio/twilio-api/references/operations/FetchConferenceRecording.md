# GET /2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Recordings/{Sid}.json

**Resource:** [Api20100401ConferenceRecording](../resources/Api20100401ConferenceRecording.md)
**Fetch an instance of a recording for a call**
**Operation ID:** `FetchConferenceRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Conference Recording resource to fetch. |
| `ConferenceSid` | path | string | Yes | The Conference SID that identifies the conference associated with the recording to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Conference Recording resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.conference.conference_recording](../schemas/api-v2010-account-conference-conference/api-v2010-account-conference-conference-recording.md)

## Security

- **accountSid_authToken**
