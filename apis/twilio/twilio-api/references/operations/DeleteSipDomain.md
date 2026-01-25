# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{Sid}.json

**Resource:** [Api20100401Domain](../resources/Api20100401Domain.md)
**Delete an instance of a Domain**
**Operation ID:** `DeleteSipDomain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the SipDomain resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the SipDomain resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
