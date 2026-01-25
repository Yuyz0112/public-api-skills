# GET /2010-04-01/Accounts/{AccountSid}/Recordings/{ReferenceSid}/AddOnResults/{AddOnResultSid}/Payloads/{Sid}.json

**Resource:** [Api20100401Payload](../resources/Api20100401Payload.md)
**Fetch an instance of a result payload**
**Operation ID:** `FetchRecordingAddOnResultPayload`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult Payload resource to fetch. |
| `ReferenceSid` | path | string | Yes | The SID of the recording to which the AddOnResult resource that contains the payload to fetch belongs. |
| `AddOnResultSid` | path | string | Yes | The SID of the AddOnResult to which the payload to fetch belongs. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording AddOnResult Payload resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.recording.recording_add_on_result.recording_add_on_result_payload](../schemas/api-v2010-account-recording-recording/api-v2010-account-recording-recording-add-on-result-recording-add-on-result-payload.md)

## Security

- **accountSid_authToken**
