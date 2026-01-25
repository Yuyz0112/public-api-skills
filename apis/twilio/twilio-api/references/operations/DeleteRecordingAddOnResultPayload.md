# DELETE /2010-04-01/Accounts/{AccountSid}/Recordings/{ReferenceSid}/AddOnResults/{AddOnResultSid}/Payloads/{Sid}.json

**Resource:** [Api20100401Payload](../resources/Api20100401Payload.md)
**Delete a payload from the result along with all associated Data**
**Operation ID:** `DeleteRecordingAddOnResultPayload`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult Payload resources to delete. |
| `ReferenceSid` | path | string | Yes | The SID of the recording to which the AddOnResult resource that contains the payloads to delete belongs. |
| `AddOnResultSid` | path | string | Yes | The SID of the AddOnResult to which the payloads to delete belongs. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording AddOnResult Payload resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
