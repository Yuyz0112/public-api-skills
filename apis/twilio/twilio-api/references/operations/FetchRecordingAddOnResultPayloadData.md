# GET /2010-04-01/Accounts/{AccountSid}/Recordings/{ReferenceSid}/AddOnResults/{AddOnResultSid}/Payloads/{PayloadSid}/Data.json

**Resource:** [Api20100401Data](../resources/Api20100401Data.md)
**Fetch an instance of a result payload**
**Operation ID:** `FetchRecordingAddOnResultPayloadData`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult Payload resource to fetch. |
| `ReferenceSid` | path | string | Yes | The SID of the recording to which the AddOnResult resource that contains the payload to fetch belongs. |
| `AddOnResultSid` | path | string | Yes | The SID of the AddOnResult to which the payload to fetch belongs. |
| `PayloadSid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording AddOnResult Payload resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 307 | Temporary Redirect |

## Security

- **accountSid_authToken**
