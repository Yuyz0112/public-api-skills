# DELETE /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Recordings/{Sid}.json

**Resource:** [Api20100401CallRecording](../resources/Api20100401CallRecording.md)
**Delete a recording from your account**
**Operation ID:** `DeleteCallRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording resources to delete. |
| `CallSid` | path | string | Yes | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID of the resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
