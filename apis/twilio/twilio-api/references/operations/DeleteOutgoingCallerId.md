# DELETE /2010-04-01/Accounts/{AccountSid}/OutgoingCallerIds/{Sid}.json

**Resource:** [Api20100401OutgoingCallerId](../resources/Api20100401OutgoingCallerId.md)
**Delete the caller-id specified from the account**
**Operation ID:** `DeleteOutgoingCallerId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the OutgoingCallerId resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the OutgoingCallerId resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
