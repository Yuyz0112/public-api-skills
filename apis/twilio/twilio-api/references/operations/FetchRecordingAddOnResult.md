# GET /2010-04-01/Accounts/{AccountSid}/Recordings/{ReferenceSid}/AddOnResults/{Sid}.json

**Resource:** [Api20100401AddOnResult](../resources/Api20100401AddOnResult.md)
**Fetch an instance of an AddOnResult**
**Operation ID:** `FetchRecordingAddOnResult`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult resource to fetch. |
| `ReferenceSid` | path | string | Yes | The SID of the recording to which the result to fetch belongs. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording AddOnResult resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.recording.recording_add_on_result](../schemas/api-v2010-account-recording-recording/api-v2010-account-recording-recording-add-on-result.md)

## Security

- **accountSid_authToken**
