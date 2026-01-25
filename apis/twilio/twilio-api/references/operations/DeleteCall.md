# DELETE /2010-04-01/Accounts/{AccountSid}/Calls/{Sid}.json

**Resource:** [Api20100401Call](../resources/Api20100401Call.md)
**Delete a Call record from your account. Once the record is deleted, it will no longer appear in the API and Account Portal logs.**
**Operation ID:** `DeleteCall`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Call resource(s) to delete. |
| `Sid` | path | string | Yes | The Twilio-provided Call SID that uniquely identifies the Call resource to delete |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
