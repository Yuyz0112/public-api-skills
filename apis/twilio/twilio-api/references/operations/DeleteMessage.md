# DELETE /2010-04-01/Accounts/{AccountSid}/Messages/{Sid}.json

**Resource:** [Api20100401Message](../resources/Api20100401Message.md)
**Deletes a Message resource from your account**
**Operation ID:** `DeleteMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with the Message resource |
| `Sid` | path | string | Yes | The SID of the Message resource you wish to delete |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
