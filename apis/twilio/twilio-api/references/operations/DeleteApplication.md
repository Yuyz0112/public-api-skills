# DELETE /2010-04-01/Accounts/{AccountSid}/Applications/{Sid}.json

**Resource:** [Api20100401Application](../resources/Api20100401Application.md)
**Delete the application by the specified application sid**
**Operation ID:** `DeleteApplication`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Application resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Application resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
