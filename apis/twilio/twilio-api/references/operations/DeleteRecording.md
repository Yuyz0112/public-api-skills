# DELETE /2010-04-01/Accounts/{AccountSid}/Recordings/{Sid}.json

**Resource:** [Api20100401Recording](../resources/Api20100401Recording.md)
**Delete a recording from your account**
**Operation ID:** `DeleteRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
