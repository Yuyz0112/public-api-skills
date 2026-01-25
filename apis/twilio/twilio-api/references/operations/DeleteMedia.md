# DELETE /2010-04-01/Accounts/{AccountSid}/Messages/{MessageSid}/Media/{Sid}.json

**Resource:** [Api20100401MediaInstance](../resources/Api20100401MediaInstance.md)
**Delete the Media resource.**
**Operation ID:** `DeleteMedia`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that is associated with the Media resource. |
| `MessageSid` | path | string | Yes | The SID of the Message resource that is associated with the Media resource. |
| `Sid` | path | string | Yes | The unique identifier of the to-be-deleted Media resource. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
