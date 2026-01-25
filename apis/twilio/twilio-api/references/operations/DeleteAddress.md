# DELETE /2010-04-01/Accounts/{AccountSid}/Addresses/{Sid}.json

**Resource:** [Api20100401Address](../resources/Api20100401Address.md)
**Operation ID:** `DeleteAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that is responsible for the Address resource to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Address resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
