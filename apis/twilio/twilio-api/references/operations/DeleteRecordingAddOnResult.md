# DELETE /2010-04-01/Accounts/{AccountSid}/Recordings/{ReferenceSid}/AddOnResults/{Sid}.json

**Resource:** [Api20100401AddOnResult](../resources/Api20100401AddOnResult.md)
**Delete a result and purge all associated Payloads**
**Operation ID:** `DeleteRecordingAddOnResult`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult resources to delete. |
| `ReferenceSid` | path | string | Yes | The SID of the recording to which the result to delete belongs. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording AddOnResult resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
