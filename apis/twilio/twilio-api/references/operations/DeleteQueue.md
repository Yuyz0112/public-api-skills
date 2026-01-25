# DELETE /2010-04-01/Accounts/{AccountSid}/Queues/{Sid}.json

**Resource:** [Api20100401Queue](../resources/Api20100401Queue.md)
**Remove an empty queue**
**Operation ID:** `DeleteQueue`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Queue resource to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Queue resource to delete |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
