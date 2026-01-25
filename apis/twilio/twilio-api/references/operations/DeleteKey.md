# DELETE /2010-04-01/Accounts/{AccountSid}/Keys/{Sid}.json

**Resource:** [Api20100401Key](../resources/Api20100401Key.md)
**Operation ID:** `DeleteKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Key resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Key resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
